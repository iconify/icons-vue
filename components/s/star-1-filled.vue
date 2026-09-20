<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_bbs_bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_bbs_bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:star-1-filled" /></template>
