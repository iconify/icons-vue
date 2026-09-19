<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms7rf3bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ms7rf3bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:shuttle-space" /></template>
