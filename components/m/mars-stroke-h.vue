<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lstl2ybmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="lstl2ybmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mars-stroke-h" /></template>
