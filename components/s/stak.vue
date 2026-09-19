<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x12q_okfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x12q_okfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:stak" /></template>
