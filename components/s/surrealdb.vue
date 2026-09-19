<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8lnf7b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l8lnf7b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:surrealdb" /></template>
