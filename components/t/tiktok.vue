<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkd0k5o0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkd0k5o0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tiktok" /></template>
