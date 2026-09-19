<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huc6u5bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="huc6u5bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:monero" /></template>
