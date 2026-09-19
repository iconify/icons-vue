<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa5ccwb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qa5ccwb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:neovim" /></template>
