<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2d4ilbfy.css';
import '../../css/s/s86v9c0wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p2d4ilbfy"/><path class="s86v9c0wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:splash-pad" /></template>
