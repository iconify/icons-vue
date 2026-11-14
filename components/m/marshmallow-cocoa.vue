<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awnykrjfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:marshmallow-cocoa" /></template>
<style>
.awnykrjfg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 3.75h.25q1.036 0 1.768.732t.732 1.768v.25q0 .397-.108.75h.358q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.25H17q3.25 0 3.25 3.25T17 15.75h-.75V17q0 1.76-1.245 3.005T12 21.25H8q-1.76 0-3.005-1.245T3.75 17V8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1V7q0-2.5 2.5-2.5h.25q1.281 0 1.906.657q.469-1.407 2.344-1.407m4.5 10.5q1.75 0 1.75-1.75T17 10.75h-.75v3.5z");
}

</style>
