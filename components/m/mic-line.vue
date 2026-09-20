<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsw1i4ejt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsw1i4ejt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mic-line" /></template>
