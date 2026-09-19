<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5gzt1b6x.css';
import '../../css/g/g0ghr3b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d5gzt1b6x"/><path class="g0ghr3b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:reactrouter-wordmark" /></template>
