<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz4fe1p6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz4fe1p6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:video-off" /></template>
