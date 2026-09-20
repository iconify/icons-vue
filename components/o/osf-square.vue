<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieh18j3cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ieh18j3cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:osf-square" /></template>
