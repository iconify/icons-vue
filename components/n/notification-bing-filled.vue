<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj0_dtb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj0_dtb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notification-bing-filled" /></template>
