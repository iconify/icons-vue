<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgwpnt3yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dgwpnt3yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-tap" /></template>
