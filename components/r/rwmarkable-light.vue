<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfcvczcbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfcvczcbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rwmarkable-light" /></template>
