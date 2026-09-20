<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eibw0yt8b.css';
import '../../css/v/v45d8qbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eibw0yt8b"/><path class="v45d8qbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microbin" /></template>
