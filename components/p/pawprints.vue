<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxlv3ga7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxlv3ga7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pawprints" /></template>
