<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7z15dbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":684,"height":1568};
const content = `<path class="u7z15dbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ralph-lauren-light" /></template>
