<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viikj1bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="viikj1bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-left-16" /></template>
