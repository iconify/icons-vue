<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5dvmebfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":448};
const content = `<path class="y5dvmebfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:triangle" /></template>
