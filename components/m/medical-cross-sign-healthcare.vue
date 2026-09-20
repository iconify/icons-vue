<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp_eg0b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hp_eg0b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:medical-cross-sign-healthcare" /></template>
