<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdzyk0bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pdzyk0bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ros" /></template>
