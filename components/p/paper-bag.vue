<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mos1fxquy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mos1fxquy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paper-bag" /></template>
