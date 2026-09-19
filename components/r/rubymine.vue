<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gti5d3bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gti5d3bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rubymine" /></template>
