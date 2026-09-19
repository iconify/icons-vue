<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crvea6bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="crvea6bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:search" /></template>
