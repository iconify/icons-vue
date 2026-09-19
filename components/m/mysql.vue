<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg2igbgln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jg2igbgln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mysql" /></template>
