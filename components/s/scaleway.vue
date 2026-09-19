<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm1yxynnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wm1yxynnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:scaleway" /></template>
