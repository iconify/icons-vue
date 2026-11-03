<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmgse00vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mmgse00vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:powerbi" /></template>
