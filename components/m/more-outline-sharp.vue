<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw710vokm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:more-outline-sharp" /></template>
<style>
.tw710vokm {
  fill: currentColor;
  d: path("m8 20l-6-8l6-8h14v16zm-3.5-8L9 18h11V6H9zM9 13h2v-2H9zm3.5 0h2v-2h-2zm3.5 0h2v-2h-2z");
}

</style>
