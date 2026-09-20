<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjm76zbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gjm76zbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tv-screen" /></template>
