<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izfv5sbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="izfv5sbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-802" /></template>
