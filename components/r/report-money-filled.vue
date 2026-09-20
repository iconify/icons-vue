<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3s8xnb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3s8xnb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:report-money-filled" /></template>
