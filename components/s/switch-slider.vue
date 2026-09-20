<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztm9i2xkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztm9i2xkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:switch-slider" /></template>
