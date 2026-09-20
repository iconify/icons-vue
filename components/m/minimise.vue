<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olol1g_ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="olol1g_ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:minimise" /></template>
