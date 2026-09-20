<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du59mfmab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="du59mfmab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medassist-dark" /></template>
