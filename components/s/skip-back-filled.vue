<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsneps5ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hsneps5ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:skip-back-filled" /></template>
