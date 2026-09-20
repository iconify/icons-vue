<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic_lku5dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic_lku5dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zx" /></template>
