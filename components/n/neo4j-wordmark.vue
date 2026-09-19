<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7agvlggf.css';
import '../../css/j/jkzqgictx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k7agvlggf"/><path class="jkzqgictx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:neo4j-wordmark" /></template>
