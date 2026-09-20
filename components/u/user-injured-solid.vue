<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwbmi7zqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nwbmi7zqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-injured-solid" /></template>
