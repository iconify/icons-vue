<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgp229bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lgp229bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pulumi" /></template>
