<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exqe1-i8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exqe1-i8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:svgtrace" /></template>
