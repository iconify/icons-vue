<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk96cpvsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kk96cpvsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:yugabytedb" /></template>
