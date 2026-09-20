<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnxp0mg7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnxp0mg7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:x-diamond-solid" /></template>
