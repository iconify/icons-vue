<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcelr4blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xcelr4blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:tennis" /></template>
