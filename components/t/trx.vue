<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-cyybcmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trx" /></template>
<style>
.o-cyybcmo {
  fill: var(--svg-color--c4342b, #c4342b);
  fill-rule: evenodd;
  d: path("M4.418 3.186a.56.56 0 0 1 .553-.17l11.904 2.915q.108.027.198.092l2.422 1.765a.564.564 0 0 1 .133.774l-8.332 12.192a.563.563 0 0 1-.998-.13L4.306 3.754a.56.56 0 0 1 .112-.568m1.965 3.045l4.16 11.711l.684-6.07zm5.957 5.838l-.695 6.175l5.884-8.61zm5.72-3.93l-3.793 1.78l2.543-2.692zm-2.395-1.343L6.41 4.53l5.426 6.32z");
}

</style>
