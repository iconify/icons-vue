<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-5b-ibab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z-5b-ibab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:trash" /></template>
