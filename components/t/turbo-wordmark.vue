<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceb8-npdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ceb8-npdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:turbo-wordmark" /></template>
