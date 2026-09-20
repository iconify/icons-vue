<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/domlw-b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":580,"height":580};
const content = `<path class="domlw-b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ragas" /></template>
