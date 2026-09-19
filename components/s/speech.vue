<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxcix4bwn.css';
import '../../css/l/ltk4tpqua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxcix4bwn"/><path class="ltk4tpqua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:speech" /></template>
