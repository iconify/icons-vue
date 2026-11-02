<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_scynb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k_scynb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:render-wordmark" /></template>
