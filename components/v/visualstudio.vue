<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzn16g15g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mzn16g15g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:visualstudio" /></template>
