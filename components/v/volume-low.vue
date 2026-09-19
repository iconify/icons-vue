<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dysnfi8qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dysnfi8qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:volume-low" /></template>
