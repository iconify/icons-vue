<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwjjx3bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwjjx3bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:taxi" /></template>
