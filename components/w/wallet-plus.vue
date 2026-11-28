<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukpiurbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukpiurbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wallet-plus" /></template>
