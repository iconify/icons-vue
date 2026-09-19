<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdk9atbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":472};
const content = `<path class="fdk9atbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:phone" /></template>
