<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rza_6mg2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rza_6mg2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:object-ungroup" /></template>
