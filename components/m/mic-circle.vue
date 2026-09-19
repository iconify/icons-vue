<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqaee4b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqaee4b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mic-circle" /></template>
