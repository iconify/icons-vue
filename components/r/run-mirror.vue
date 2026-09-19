<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idd3-bjtr.css';
import '../../css/i/ifbp0ub9u.css';
import '../../css/f/fp0jp3bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="idd3-bjtr"/><path class="ifbp0ub9u"/><path class="fp0jp3bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:run-mirror" /></template>
