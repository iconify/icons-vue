<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udnf6hbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udnf6hbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:scan-face-x" /></template>
