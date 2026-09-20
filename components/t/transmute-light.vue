<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5-xe2bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5-xe2bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:transmute-light" /></template>
