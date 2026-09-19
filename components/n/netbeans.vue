<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu1p7nb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mu1p7nb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:netbeans" /></template>
