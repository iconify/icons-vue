<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qghjcac2i.css';
import '../../css/s/smcke3big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qghjcac2i"/><path class="smcke3big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tide-low-20-bold" /></template>
