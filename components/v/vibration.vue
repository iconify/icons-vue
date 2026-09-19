<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf25d2r7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="mf25d2r7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:vibration" /></template>
