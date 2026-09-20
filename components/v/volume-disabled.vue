<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1pi9x57x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="n1pi9x57x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:volume-disabled" /></template>
