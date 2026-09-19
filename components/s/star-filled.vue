<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhqi00bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhqi00bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:star-filled" /></template>
