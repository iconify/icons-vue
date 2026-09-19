<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akpogxbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="akpogxbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:search" /></template>
