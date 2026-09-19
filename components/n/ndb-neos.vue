<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j0kkunbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ndb-neos" /></template>
<style>
.j0kkunbqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.293 8.052L5.5 23.361V8.052zm6.379 6.379L11.88 42.5h26.792zM5.5 28.465V42.5l37-37z");
}

</style>
