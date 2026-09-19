<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj9vw7x9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="nj9vw7x9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:road-bridge" /></template>
