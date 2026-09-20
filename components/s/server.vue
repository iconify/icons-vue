<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjdee8b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sjdee8b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:server" /></template>
