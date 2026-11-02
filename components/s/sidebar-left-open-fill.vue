<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx8fw-bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx8fw-bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sidebar-left-open-fill" /></template>
