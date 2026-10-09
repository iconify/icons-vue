<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrs6n7bep.css';
import '../../css/w/w2gzq9yrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nrs6n7bep"/><path class="w2gzq9yrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wattmeter-20" /></template>
