<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs0kbjd4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zs0kbjd4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nano" /></template>
