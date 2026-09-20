<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3uc9rd7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3uc9rd7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:vdi-folder" /></template>
