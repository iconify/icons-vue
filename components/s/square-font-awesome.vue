<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld8aljbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ld8aljbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-font-awesome" /></template>
