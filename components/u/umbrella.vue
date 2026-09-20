<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmwrbob4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="kmwrbob4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:umbrella" /></template>
