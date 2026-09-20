<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiy1g7h8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiy1g7h8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:qualcomm-logo" /></template>
