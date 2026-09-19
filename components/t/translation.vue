<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slplf4wxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="slplf4wxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:translation" /></template>
