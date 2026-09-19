<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpnkkoitm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpnkkoitm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:trash-can" /></template>
