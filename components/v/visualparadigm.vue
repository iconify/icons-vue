<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc2q2zbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nc2q2zbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:visualparadigm" /></template>
