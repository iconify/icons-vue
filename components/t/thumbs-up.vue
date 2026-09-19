<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv0hl_r7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vv0hl_r7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:thumbs-up" /></template>
