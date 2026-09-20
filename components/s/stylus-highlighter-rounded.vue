<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae69t7jcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-highlighter-rounded" /></template>
<style>
.ae69t7jcg {
  fill: currentColor;
  d: path("M8.48 15.308q-.347 0-.577-.23t-.23-.578V5.616q0-.672.472-1.144T9.29 4q.186 0 .363.04t.339.121l5.403 2.649q.423.211.669.603t.245.85V14.5q0 .348-.23.578t-.578.23zM6.145 20q-.423 0-.658-.335q-.236-.336-.1-.74l.087-.242q.162-.452.533-.721t.848-.27h10.292q.477 0 .848.27t.533.72l.087.243q.136.404-.1.74q-.235.335-.658.335z");
}

</style>
