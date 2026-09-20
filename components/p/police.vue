<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjic3kb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kjic3kb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:police" /></template>
