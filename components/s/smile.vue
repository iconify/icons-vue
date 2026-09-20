<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvffxab-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zvffxab-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:smile" /></template>
