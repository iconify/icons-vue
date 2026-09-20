<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxlfg-bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxlfg-bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volume-up3-filled" /></template>
