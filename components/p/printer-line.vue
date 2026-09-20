<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r44tmacvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r44tmacvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:printer-line" /></template>
