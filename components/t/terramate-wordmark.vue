<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8ebn724t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="b8ebn724t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:terramate-wordmark" /></template>
