<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk4kwybym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="xk4kwybym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:neg-2" /></template>
