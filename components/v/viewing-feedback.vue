<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqpjwkbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:viewing-feedback" /></template>
<style>
.jqpjwkbrt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 1.75H5q-1.346 0-2.298.952T1.75 5v9.5q0 3.25 3.25 3.25h4.114l2.276 3.186q.072.102.174.174q.06.043.128.074q.067.03.139.047q.072.016.146.019q.073.002.146-.01t.142-.038q.069-.027.132-.066t.117-.089q.053-.051.096-.111l2.276-3.186H19q3.25 0 3.25-3.25V5q0-1.346-.952-2.298T19 1.75m-5.74 4.859l.001.002l.238.482q.175.353.565.41l.534.078q.865.125 1.135.956q.27.832-.357 1.442l-.385.376q-.283.275-.217.664l.092.53q.149.862-.559 1.376q-.707.514-1.481.106l-.477-.25q-.349-.184-.698 0l-.478.251q-.773.407-1.48-.107q-.708-.514-.559-1.376l.092-.532q.066-.387-.216-.662l-.387-.377q-.626-.609-.356-1.441q.27-.831 1.136-.956l.533-.078q.39-.057.565-.41l.239-.484q.384-.784 1.26-.784q.875 0 1.26.784");
}

</style>
