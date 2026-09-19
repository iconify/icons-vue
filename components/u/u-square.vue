<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y363cibox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="y363cibox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:u-square" /></template>
