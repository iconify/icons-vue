<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiqw2lbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="jiqw2lbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:more-horiz" /></template>
