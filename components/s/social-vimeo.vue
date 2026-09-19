<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmetgsbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bmetgsbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-vimeo" /></template>
