<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivbs_oy6v.css';
import '../../css/g/ghclb9bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ivbs_oy6v"/><path class="ghclb9bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sanity" /></template>
