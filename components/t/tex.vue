<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rihk17bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rihk17bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tex" /></template>
