<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4cv7lb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g4cv7lb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:mr" /></template>
