<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfx4nus2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cfx4nus2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:ussunnah" /></template>
