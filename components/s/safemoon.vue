<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwz3jeuga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cwz3jeuga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:safemoon" /></template>
