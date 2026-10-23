<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we0b_qrdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we0b_qrdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ribbon" /></template>
