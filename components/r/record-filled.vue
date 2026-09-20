<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uesya8onb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uesya8onb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:record-filled" /></template>
