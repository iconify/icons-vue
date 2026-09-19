<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn37jeqpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pn37jeqpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:stamp" /></template>
