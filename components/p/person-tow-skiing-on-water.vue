<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucghxkb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ucghxkb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-tow-skiing-on-water" /></template>
