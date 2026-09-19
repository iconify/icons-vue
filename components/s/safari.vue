<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhwn_b2xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uhwn_b2xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:safari" /></template>
