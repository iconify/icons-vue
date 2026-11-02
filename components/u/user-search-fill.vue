<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbn3dmb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbn3dmb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-search-fill" /></template>
