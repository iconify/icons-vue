<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxtz1bcbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxtz1bcbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:volleyball-fill" /></template>
