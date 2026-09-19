<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va95obcov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="va95obcov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:phone-remove" /></template>
