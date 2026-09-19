<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4c5z7bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m4c5z7bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:mysql" /></template>
