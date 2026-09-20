<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mws_x1bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:map-outline-sharp" /></template>
<style>
.mws_x1bvy {
  fill: currentColor;
  d: path("m15 19.923l-6-2.1l-5 1.94V5.782l5-1.704l6 2.1l5-1.94v14.04zm-.5-1.22v-11.7l-5-1.745v11.7zm1 0L19 17.55V5.7l-3.5 1.304zM5 18.3l3.5-1.342v-11.7L5 6.45zM15.5 7.004v11.7zm-7-1.746v11.7z");
}

</style>
