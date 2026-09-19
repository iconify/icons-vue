<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9bs2gbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k9bs2gbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:record" /></template>
