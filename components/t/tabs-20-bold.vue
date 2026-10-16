<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_a0sffvb.css';
import '../../css/f/fan1dzboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b_a0sffvb"/><path class="fan1dzboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tabs-20-bold" /></template>
