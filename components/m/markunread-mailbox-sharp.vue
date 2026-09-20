<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyyfqbyde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:markunread-mailbox-sharp" /></template>
<style>
.oyyfqbyde {
  fill: currentColor;
  d: path("M2 22V8h4V2h8v4H8v8h2V8h12v14z");
}

</style>
