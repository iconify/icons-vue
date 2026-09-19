<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crzcs7bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crzcs7bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:widget-filled" /></template>
