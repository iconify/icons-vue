<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2fgik1my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="w2fgik1my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:sheriff-badge" /></template>
