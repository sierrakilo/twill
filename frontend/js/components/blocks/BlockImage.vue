<template>
  <div class="block__body">
    <a17-inputframe label="Image" name="medias.image">
      <a17-mediafield :name="fieldName('image')" crop-context="image"></a17-mediafield>
    </a17-inputframe>
  </div>
</template>

<script>
  import BlockMixin from '@/mixins/block'

  export default {
    name: 'A17Image',
    mixins: [BlockMixin]
  }
</script>
