<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix5i5ubsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ix5i5ubsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:socketdotio-dark" /></template>
