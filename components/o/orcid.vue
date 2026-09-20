<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swxpzcv9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swxpzcv9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:orcid" /></template>
