<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czjjpdb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="czjjpdb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:typo3" /></template>
