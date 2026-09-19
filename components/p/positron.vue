<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da-peabtg.css';
import '../../css/u/udo33x03z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<rect class="da-peabtg"/><path class="udo33x03z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:positron" /></template>
