<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7k91wbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x7k91wbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:operating-system-settings" /></template>
