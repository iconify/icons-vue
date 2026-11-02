<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue30s2b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ue30s2b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pocketbase-wordmark" /></template>
