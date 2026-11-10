<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cevse_boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cevse_boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:square-brackets-off" /></template>
