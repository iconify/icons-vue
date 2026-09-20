<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy6pjk5oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oy6pjk5oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:mushroom" /></template>
