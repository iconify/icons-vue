<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfkmsnb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfkmsnb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:regionalindicators" /></template>
