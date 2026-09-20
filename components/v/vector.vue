<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp8_wcczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cp8_wcczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:vector" /></template>
