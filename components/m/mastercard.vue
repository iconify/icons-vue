<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2ct9t3oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g2ct9t3oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:mastercard" /></template>
