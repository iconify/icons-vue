<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhdgbeb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mhdgbeb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:pied-piper-alt" /></template>
