<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwapst6yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwapst6yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:pinwheel-line" /></template>
