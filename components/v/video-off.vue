<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljwd1_bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljwd1_bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:video-off" /></template>
