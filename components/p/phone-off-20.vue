<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe9koubop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oe9koubop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-off-20" /></template>
