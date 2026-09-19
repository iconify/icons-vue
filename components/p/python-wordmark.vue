<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdaxtuzta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tdaxtuzta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:python-wordmark" /></template>
