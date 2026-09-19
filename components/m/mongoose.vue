<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5nmllbgc.css';
import '../../css/m/m3qb8jb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t5nmllbgc"/><path class="m3qb8jb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mongoose" /></template>
