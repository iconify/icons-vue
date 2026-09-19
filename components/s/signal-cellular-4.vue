<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyl1b_bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tyl1b_bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:signal-cellular-4" /></template>
