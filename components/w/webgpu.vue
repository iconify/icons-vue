<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd8ne7a8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fd8ne7a8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:webgpu" /></template>
