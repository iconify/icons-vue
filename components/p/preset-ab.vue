<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm4sl1b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tm4sl1b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:preset-ab" /></template>
