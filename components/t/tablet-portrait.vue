<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twpo036bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="twpo036bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:tablet-portrait" /></template>
