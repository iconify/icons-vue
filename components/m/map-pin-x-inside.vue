<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxrrs146k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxrrs146k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:map-pin-x-inside" /></template>
