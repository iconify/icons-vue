<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7_v_006l.css';
import '../../css/o/ort-_6bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g7_v_006l"/><path class="ort-_6bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:variable-resistor-20-bold" /></template>
