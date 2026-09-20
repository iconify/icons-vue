<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm6p1mtnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm6p1mtnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-3-filled" /></template>
