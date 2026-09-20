<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu0vqebuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gu0vqebuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:script" /></template>
