<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjvowy43g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tjvowy43g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:passport-wordmark" /></template>
