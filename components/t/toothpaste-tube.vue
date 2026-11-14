<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1kynhbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:toothpaste-tube" /></template>
<style>
.z1kynhbuj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.597 3.514l-.708.707v.001q-.64.639-.721 1.51q-.318-.016-.662.052l-.464.093q-.602.12-1.08.505l-8.034 6.48q.094-.022.19-.021q.097.002.19.028t.177.075t.151.117l5.303 5.303q.069.068.117.151q.049.084.075.177t.028.19q.001.096-.021.19l6.48-8.034q.385-.478.506-1.081l.091-.462q.069-.345.053-.663q.871-.081 1.511-.721l.707-.708q1.765-1.767-.001-3.534l-.354-.355q-1.767-1.765-3.534 0m-5.86 16.054q-.155.076-.328.076q-.149 0-.287-.057t-.243-.163l-5.303-5.303q-.106-.105-.163-.243t-.057-.287q0-.173.076-.328l-.579.466q-.868.7-.927 1.813t.729 1.901l2.902 2.902q.788.789 1.901.729q1.113-.059 1.813-.927z");
}

</style>
