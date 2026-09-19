<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhxkqmbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vhxkqmbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-web-awesome" /></template>
