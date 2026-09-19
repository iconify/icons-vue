<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1nh42b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l1nh42b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:medical-cross" /></template>
