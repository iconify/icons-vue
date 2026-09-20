<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4wqug1if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:quidd" /></template>
<style>
.q4wqug1if {
  fill: var(--svg-color--6b10d7, #6b10d7);
  d: path("M17.294 19.279a9 9 0 1 0-2.647 1.323v-4.018a5.294 5.294 0 1 1 2.647-4.585zm-5.295-4.633a2.648 2.648 0 1 0 0-5.295a2.648 2.648 0 0 0 0 5.295");
}

</style>
