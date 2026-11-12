<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oshvhvbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="oshvhvbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:turborepo" /></template>
