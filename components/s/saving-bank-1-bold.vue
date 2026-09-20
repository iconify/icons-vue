<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crs964q4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crs964q4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:saving-bank-1-bold" /></template>
