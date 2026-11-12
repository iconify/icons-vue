<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngfmjsmvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ngfmjsmvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rahoot" /></template>
