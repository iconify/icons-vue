<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-spsjb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="d-spsjb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:voice-mail-off" /></template>
