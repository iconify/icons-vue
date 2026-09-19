<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbx0ibcmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tbx0ibcmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:menu-alt" /></template>
