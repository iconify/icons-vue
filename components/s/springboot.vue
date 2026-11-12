<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya06mob_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ya06mob_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:springboot" /></template>
