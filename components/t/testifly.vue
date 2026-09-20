<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca41jjffc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ca41jjffc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:testifly" /></template>
