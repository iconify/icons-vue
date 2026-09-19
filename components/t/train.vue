<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5cv9757k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="q5cv9757k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:train" /></template>
