<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0ymcdb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-pen" /></template>
<style>
.p0ymcdb7b {
  fill: currentColor;
  d: path("m6.885 15.308l2.134-8.174h1.539V5.788L11.788 3h.424l1.25 2.789v1.346H15l2.135 8.173zM5 20l.473-1.317q.162-.452.533-.722t.848-.269h10.292q.477 0 .848.27t.533.72L19 20z");
}

</style>
