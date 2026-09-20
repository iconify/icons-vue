<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx7djlehs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wx7djlehs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:medical-cross" /></template>
