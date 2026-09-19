<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wicxrwbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wicxrwbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:percentage-filled" /></template>
