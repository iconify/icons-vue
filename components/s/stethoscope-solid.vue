<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te73lab3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="te73lab3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:stethoscope-solid" /></template>
