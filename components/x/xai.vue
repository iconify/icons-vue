<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5lllnndj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n5lllnndj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:xai" /></template>
