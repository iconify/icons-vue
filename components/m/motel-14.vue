<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewpv6-bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ewpv6-bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:motel-14" /></template>
