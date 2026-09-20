<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v75o0q40y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v75o0q40y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openwrt-dark" /></template>
