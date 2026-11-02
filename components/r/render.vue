<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svr_m0wrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="svr_m0wrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:render" /></template>
