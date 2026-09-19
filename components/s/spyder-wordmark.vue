<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy64nx-nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sy64nx-nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:spyder-wordmark" /></template>
