<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwh0__bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nwh0__bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:venus-double-solid" /></template>
