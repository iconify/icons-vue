<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzj8i4mvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1080};
const content = `<path clip-rule="evenodd" class="tzj8i4mvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:wash-bicycle-14" /></template>
