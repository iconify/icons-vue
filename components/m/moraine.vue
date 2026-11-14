<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om-g8zb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:moraine" /></template>
<style>
.om-g8zb8r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.1 11.117l.974-3.574q.304-1.111 1.382-1.514l1.739-.653q.931-.349 1.816.103q.884.453 1.146 1.412l.799 2.929q.078.286.094.551q.141.015.286.047l2.975.661q1.277.283 1.663 1.534l1.146 3.725q.334 1.086-.341 1.999t-1.81.913H12q-.951 0-1.5-.402q-.549.402-1.5.402H4.921q-1.098 0-1.773-.866q-.676-.865-.41-1.93l.379-1.515q.233-.932 1.067-1.408l2.247-1.284q.28-.16.563-.239q-.025-.411.106-.891");
}

</style>
