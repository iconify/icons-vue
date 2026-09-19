<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkpaxnb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wkpaxnb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:unlink-outline" /></template>
