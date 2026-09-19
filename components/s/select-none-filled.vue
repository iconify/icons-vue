<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/houfp_bzv.css';
import '../../css/h/h8_ziyb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="houfp_bzv"/><path class="h8_ziyb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:select-none-filled" /></template>
