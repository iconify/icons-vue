<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i08er2b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="i08er2b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:storybook" /></template>
