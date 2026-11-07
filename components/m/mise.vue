<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i90kd3j_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="i90kd3j_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mise" /></template>
