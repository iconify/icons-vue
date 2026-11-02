<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8aqjnb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h8aqjnb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vlang" /></template>
