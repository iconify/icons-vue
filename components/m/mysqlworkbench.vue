<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htnqb_kqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="htnqb_kqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:mysqlworkbench" /></template>
