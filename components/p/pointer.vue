<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6iivnbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":638,"height":694};
const content = `<path class="m6iivnbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:pointer" /></template>
