<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9vlg2rrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9vlg2rrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:ravelry" /></template>
