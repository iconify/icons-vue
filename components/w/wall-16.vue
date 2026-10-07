<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1hyej7ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1hyej7ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:wall-16" /></template>
