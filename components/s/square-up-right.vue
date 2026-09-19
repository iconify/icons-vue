<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np56-gb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="np56-gb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-up-right" /></template>
