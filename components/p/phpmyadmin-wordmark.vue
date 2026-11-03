<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1swtpa_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r1swtpa_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:phpmyadmin-wordmark" /></template>
