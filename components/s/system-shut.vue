<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imrr2wcsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imrr2wcsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:system-shut" /></template>
