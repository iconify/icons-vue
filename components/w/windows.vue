<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kngy64yfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":408};
const content = `<path class="kngy64yfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:windows" /></template>
