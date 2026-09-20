<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b14u329ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b14u329ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:ssrn" /></template>
