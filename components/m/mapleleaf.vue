<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha8_tdyso.css';
import '../../css/r/r0ghz7b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ha8_tdyso"/><path class="r0ghz7b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:mapleleaf" /></template>
