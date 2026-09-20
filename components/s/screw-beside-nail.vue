<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yimgu8b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yimgu8b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:screw-beside-nail" /></template>
