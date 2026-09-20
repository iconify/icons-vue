<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icdflt42b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icdflt42b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:scan-solid" /></template>
