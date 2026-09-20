<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt816lcdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt816lcdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vip-off" /></template>
