<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xykl8zb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-dot-fill" /></template>
<style>
.xykl8zb4t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5645 2C15.4927 2.0001 16.3829 2.369 17.0391 3.0254L20.9746 6.9609C21.631 7.6171 21.9999 8.5073 22 9.4355L22 14.5645C21.9999 15.4927 21.631 16.3829 20.9746 17.0391L17.0391 20.9746C16.3829 21.631 15.4927 21.9999 14.5645 22L9.4355 22C8.5073 21.9999 7.6171 21.631 6.9609 20.9746L3.0254 17.0391C2.369 16.3829 2.0001 15.4927 2 14.5645L2 9.4355C2.0001 8.5073 2.369 7.6171 3.0254 6.9609L6.9609 3.0254C7.6171 2.369 8.5073 2.0001 9.4355 2L14.5645 2ZM14 12C14 10.8954 13.1046 10 12 10C10.8954 10 10 10.8954 10 12C10 13.1046 10.8954 14 12 14C13.1046 14 14 13.1046 14 12Z");
}

</style>
