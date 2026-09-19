<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rea25db9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rea25db9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:plus" /></template>
