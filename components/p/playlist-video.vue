<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a71b_4pwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a71b_4pwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:playlist-video" /></template>
