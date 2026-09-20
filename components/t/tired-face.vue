<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhslucb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zhslucb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face" /></template>
