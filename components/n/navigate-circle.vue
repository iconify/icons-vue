<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh5b57bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xh5b57bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:navigate-circle" /></template>
