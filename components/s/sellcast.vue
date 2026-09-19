<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzxff1zbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="uzxff1zbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:sellcast" /></template>
