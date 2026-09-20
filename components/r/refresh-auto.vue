<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zupxrzsac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zupxrzsac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:refresh-auto" /></template>
