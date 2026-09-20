<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="f3rqm576h"/><path class="escz3yb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:warning" /></template>
<style>
.escz3yb8x {
  fill: var(--svg-color--231f20, #231f20);
  d: path("M15.583 28.953a2.42 2.42 0 0 1 2.419-2.418a2.42 2.42 0 0 1 2.418 2.418a2.42 2.42 0 0 1-2.418 2.419a2.42 2.42 0 0 1-2.419-2.419m.186-18.293c0-1.302.961-2.108 2.232-2.108c1.241 0 2.233.837 2.233 2.108v11.938c0 1.271-.992 2.108-2.233 2.108c-1.271 0-2.232-.807-2.232-2.108z");
}

.f3rqm576h {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M2.653 35C.811 35-.001 33.662.847 32.027L16.456 1.972c.849-1.635 2.238-1.635 3.087 0l15.609 30.056c.85 1.634.037 2.972-1.805 2.972z");
}

</style>
