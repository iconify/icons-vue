<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb7tl124z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bb7tl124z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:webgl" /></template>
