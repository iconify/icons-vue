<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdsiym1km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vdsiym1km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pint-sharp" /></template>
