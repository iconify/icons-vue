<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqn-v9b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="iqn-v9b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:receipt" /></template>
