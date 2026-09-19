<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deso3sbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="deso3sbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:spring-wordmark" /></template>
