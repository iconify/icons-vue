<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he60uobfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="he60uobfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:storefront" /></template>
