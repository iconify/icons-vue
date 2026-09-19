<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd1j9ig9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":408};
const content = `<path class="jd1j9ig9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:network-wifi-scan" /></template>
