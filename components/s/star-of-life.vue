<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3xkxxb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3xkxxb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:star-of-life" /></template>
