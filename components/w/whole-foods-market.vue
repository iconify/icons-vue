<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiftlgbea.css';
import '../../css/i/ix4gy1bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":684.206};
const content = `<path class="kiftlgbea"/><path class="ix4gy1bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:whole-foods-market" /></template>
