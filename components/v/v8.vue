<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpf3z12ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wpf3z12ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:v8" /></template>
