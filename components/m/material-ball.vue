<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3l90en_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:material-ball" /></template>
<style>
.t3l90en_g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m.6 8.42q-.012-.072-.011-.146t.018-.146q.016-.072.046-.14t.072-.128q.042-.061.095-.112q.054-.051.116-.091q.062-.039.131-.066t.142-.04q.147-.026.292.007q.146.032.268.118t.203.211q.08.126.106.273q.765 4.338 5.17 4.338q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .149-.057.287t-.163.243t-.243.163q-.138.057-.287.057q-5.664 0-6.648-5.578");
}

</style>
