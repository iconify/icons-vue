<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8dze2bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="s8dze2bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tint-slash" /></template>
