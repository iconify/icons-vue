<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1g1p6r1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w1g1p6r1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:networkx" /></template>
