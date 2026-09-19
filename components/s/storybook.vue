<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swtjpbc4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="swtjpbc4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:storybook" /></template>
