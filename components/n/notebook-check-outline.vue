<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrneegkxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrneegkxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notebook-check-outline" /></template>
