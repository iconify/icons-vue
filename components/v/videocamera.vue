<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq1hgyzbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":750};
const content = `<path class="cq1hgyzbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:videocamera" /></template>
