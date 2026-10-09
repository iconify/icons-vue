<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxh9rydyd.css';
import '../../css/a/aexs-bb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kxh9rydyd"/><path class="aexs-bb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sailboat-20-bold" /></template>
