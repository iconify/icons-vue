<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cugs406to.css';
import '../../css/z/zrzrd2cbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cugs406to"/><path class="zrzrd2cbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:protractor-20" /></template>
