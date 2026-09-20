<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj8grqbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tj8grqbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:weebly" /></template>
