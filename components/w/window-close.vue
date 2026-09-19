<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfb-jbbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfb-jbbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:window-close" /></template>
