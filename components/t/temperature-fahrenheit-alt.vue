<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovmg3j_6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ovmg3j_6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-fahrenheit-alt" /></template>
