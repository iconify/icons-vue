<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdfx8mbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rdfx8mbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:ruby" /></template>
