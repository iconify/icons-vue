<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxr05_b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1227};
const content = `<path class="nxr05_b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:x-formerly-twitter-dark" /></template>
