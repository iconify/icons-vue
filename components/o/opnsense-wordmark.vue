<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwzr932tw.css';
import '../../css/s/s1cvkxb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cwzr932tw"/><path class="s1cvkxb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:opnsense-wordmark" /></template>
