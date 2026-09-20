<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqquaabfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:personal-places-rounded" /></template>
<style>
.uqquaabfk {
  fill: currentColor;
  d: path("M7 19V6.039q0-.441.299-.74T8.039 5h7.103q.404 0 .762.187q.358.186.575.51l1.644 2.384q.293.429.293.919t-.293.92l-1.644 2.384q-.217.323-.575.51q-.358.186-.762.186H8v6q0 .214-.143.357T7.5 19.5t-.357-.143T7 19");
}

</style>
