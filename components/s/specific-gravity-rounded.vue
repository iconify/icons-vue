<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woj2g-bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:specific-gravity-rounded" /></template>
<style>
.woj2g-bcw {
  fill: currentColor;
  d: path("M7 22q-.775 0-1.35-.5T5 20.225L3.125 3.1q-.05-.45.25-.775T4.125 2h15.75q.45 0 .75.325t.25.775L19 20.225q-.075.775-.65 1.275T17 22zM5.675 8H9.35q.525-.475 1.2-.737T12 7t1.45.263t1.2.737h3.675l.425-4H5.225zM12 13q.825 0 1.413-.587T14 11t-.587-1.412T12 9t-1.412.588T10 11t.588 1.413T12 13");
}

</style>
