<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axqjiccfh.css';
import '../../css/n/nuioz00-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="axqjiccfh"/><path class="nuioz00-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stimulus-wordmark" /></template>
