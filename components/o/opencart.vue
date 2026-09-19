<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obyc_pxxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2336,"height":1664};
const content = `<path class="obyc_pxxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:opencart" /></template>
