<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q125_acrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q125_acrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tennessee" /></template>
