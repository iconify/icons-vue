<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxcxvetxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-phone-sharp" /></template>
<style>
.oxcxvetxn {
  fill: currentColor;
  d: path("M10.845 10.54q-.23-.23-.23-.54t.23-.54t.54-.23t.539.23t.23.54t-.23.54t-.54.23t-.539-.23m4.54.23q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.539.23t.23.54t-.23.54t-.54.23m4 0q-.309 0-.539-.23t-.23-.54t.23-.54t.54-.23t.539.23t.23.54t-.23.54t-.54.23M19.2 20q-2.702 0-5.418-1.244t-5.005-3.533q-2.27-2.289-3.523-5.021Q4 7.469 4 4.8V4h4.439l.848 4.083l-2.696 2.51q.684 1.186 1.417 2.167t1.527 1.769q.802.84 1.808 1.57t2.296 1.44l2.611-2.708l3.75.756V20z");
}

</style>
