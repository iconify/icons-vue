<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov3hmsk9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov3hmsk9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-refresh" /></template>
