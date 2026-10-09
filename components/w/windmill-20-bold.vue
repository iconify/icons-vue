<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ist7qnbhr.css';
import '../../css/v/vhdemacnv.css';
import '../../css/o/o1-sdirwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ist7qnbhr"/><path class="vhdemacnv"/><path class="o1-sdirwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:windmill-20-bold" /></template>
