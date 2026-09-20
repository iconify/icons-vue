<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5pwsvboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1545,"height":1151};
const content = `<path class="o5pwsvboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:onex" /></template>
