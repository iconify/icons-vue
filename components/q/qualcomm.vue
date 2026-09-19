<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo7nucb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oo7nucb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:qualcomm" /></template>
