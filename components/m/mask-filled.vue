<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqog2_b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqog2_b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mask-filled" /></template>
