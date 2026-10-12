<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0zdwccrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l0zdwccrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-fill-20" /></template>
