<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekntucc5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ekntucc5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:recycling-14" /></template>
