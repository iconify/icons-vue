<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gugo44b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gugo44b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:scan-small" /></template>
