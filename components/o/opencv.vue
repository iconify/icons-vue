<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgg2hac1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dgg2hac1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:opencv" /></template>
