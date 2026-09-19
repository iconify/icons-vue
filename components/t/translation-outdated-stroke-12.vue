<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/und8i-7ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="und8i-7ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-outdated-stroke-12" /></template>
