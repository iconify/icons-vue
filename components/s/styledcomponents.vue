<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt7mp2tnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kt7mp2tnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:styledcomponents" /></template>
