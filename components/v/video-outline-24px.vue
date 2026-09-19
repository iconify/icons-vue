<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2nz1si5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2nz1si5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:video-outline-24px" /></template>
