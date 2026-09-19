<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bb4kn2bbl.css';
import '../../css/q/q1uhlqbuy.css';
import '../../css/l/ljvvjtnlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="bb4kn2bbl"/><path class="q1uhlqbuy"/><path class="ljvvjtnlp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-walking" /></template>
