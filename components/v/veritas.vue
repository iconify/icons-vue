<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvjmh0b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvjmh0b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:veritas" /></template>
