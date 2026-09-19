<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7bx3lbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o7bx3lbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:moleculer" /></template>
