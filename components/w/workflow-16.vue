<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut0ox1teu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ut0ox1teu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:workflow-16" /></template>
