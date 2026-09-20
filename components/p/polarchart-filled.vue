<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4-h6-tbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="g4-h6-tbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:polarchart-filled" /></template>
