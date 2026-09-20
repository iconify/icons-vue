<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuc8ibcpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vuc8ibcpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:text" /></template>
