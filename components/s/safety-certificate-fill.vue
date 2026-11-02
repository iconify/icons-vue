<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j23q30xfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j23q30xfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safety-certificate-fill" /></template>
