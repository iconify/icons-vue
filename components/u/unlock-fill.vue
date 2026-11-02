<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvfdzzyfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvfdzzyfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unlock-fill" /></template>
