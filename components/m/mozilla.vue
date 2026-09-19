<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i28o-pnrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i28o-pnrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:mozilla" /></template>
