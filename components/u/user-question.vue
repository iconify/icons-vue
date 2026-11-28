<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1kcf2va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1kcf2va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-question" /></template>
