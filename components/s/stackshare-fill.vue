<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-7_-31ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-7_-31ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stackshare-fill" /></template>
