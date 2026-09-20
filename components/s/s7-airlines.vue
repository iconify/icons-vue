<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amc1uab8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amc1uab8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:s7-airlines" /></template>
