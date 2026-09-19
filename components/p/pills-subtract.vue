<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maueyoblv.css';
import '../../css/l/lk5_xc46y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="maueyoblv"/><path class="lk5_xc46y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pills-subtract" /></template>
