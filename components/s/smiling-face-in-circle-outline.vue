<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lich9zb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lich9zb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:smiling-face-in-circle-outline" /></template>
