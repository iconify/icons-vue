<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl1bm0zko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jl1bm0zko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:supabase" /></template>
