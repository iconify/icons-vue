<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niq-ey43z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niq-ey43z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:twitter" /></template>
