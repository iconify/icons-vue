<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5_st3wlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:package-2-sharp" /></template>
<style>
.r5_st3wlw {
  fill: currentColor;
  d: path("M11.5 20.86v-8.573L4 7.95v8.598zm1 0l7.5-4.312V7.95l-7.5 4.337zm3.667-11.846l3.277-1.88L12 2.855L8.775 4.708zM12 11.427l3.167-1.835L7.742 5.3L4.57 7.121z");
}

</style>
