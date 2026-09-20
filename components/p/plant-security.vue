<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nge3vp00y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nge3vp00y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-security" /></template>
