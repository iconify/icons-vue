<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp44u9h7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp44u9h7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:twitter-fill" /></template>
