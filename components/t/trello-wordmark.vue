<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw2o4bb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bw2o4bb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:trello-wordmark" /></template>
