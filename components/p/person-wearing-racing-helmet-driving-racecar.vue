<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq14dwolm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qq14dwolm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-racing-helmet-driving-racecar" /></template>
