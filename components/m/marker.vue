<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epcjm8b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epcjm8b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:marker" /></template>
