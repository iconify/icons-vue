<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruiztq3ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ruiztq3ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:opengl" /></template>
