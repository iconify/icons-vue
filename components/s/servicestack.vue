<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slkefgbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="slkefgbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:servicestack" /></template>
