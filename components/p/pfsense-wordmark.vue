<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_e3xfbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="b_e3xfbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pfsense-wordmark" /></template>
