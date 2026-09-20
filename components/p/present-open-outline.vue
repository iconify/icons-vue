<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysj7deb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysj7deb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:present-open-outline" /></template>
