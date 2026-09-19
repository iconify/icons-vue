<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1ux52a_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1792};
const content = `<path class="r1ux52a_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:thermometer" /></template>
