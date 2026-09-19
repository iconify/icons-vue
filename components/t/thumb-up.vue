<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th2m307zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="th2m307zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:thumb-up" /></template>
