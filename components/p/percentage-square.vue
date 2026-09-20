<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-n5pnb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-n5pnb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:percentage-square" /></template>
