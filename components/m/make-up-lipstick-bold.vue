<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwv-ctbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwv-ctbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:make-up-lipstick-bold" /></template>
