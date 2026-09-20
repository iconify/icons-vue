<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhc6vccdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fhc6vccdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mountain" /></template>
