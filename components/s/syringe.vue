<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuwt53rzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uuwt53rzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:syringe" /></template>
