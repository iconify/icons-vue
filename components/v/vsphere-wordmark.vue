<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf7bh81uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bf7bh81uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vsphere-wordmark" /></template>
