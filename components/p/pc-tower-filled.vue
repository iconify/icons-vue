<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thaxyb7jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="thaxyb7jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pc-tower-filled" /></template>
