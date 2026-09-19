<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/damadsbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="damadsbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:minus-square" /></template>
