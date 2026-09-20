<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6s0uv0ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w6s0uv0ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:spack" /></template>
