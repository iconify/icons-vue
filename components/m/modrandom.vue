<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q14unqb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q14unqb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:modrandom" /></template>
