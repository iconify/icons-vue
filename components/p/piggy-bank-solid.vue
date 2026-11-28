<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qilmos39e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qilmos39e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:piggy-bank-solid" /></template>
