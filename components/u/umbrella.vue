<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrh2svbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="qrh2svbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:umbrella" /></template>
