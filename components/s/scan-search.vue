<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rka33acyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rka33acyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-search" /></template>
