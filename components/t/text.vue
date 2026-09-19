<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-wusac0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-wusac0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:text" /></template>
