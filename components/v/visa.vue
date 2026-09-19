<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly_3qfbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly_3qfbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:visa" /></template>
