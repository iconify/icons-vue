<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkeo62b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rkeo62b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:matlab" /></template>
