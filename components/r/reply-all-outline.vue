<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmlb6r02r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmlb6r02r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:reply-all-outline" /></template>
