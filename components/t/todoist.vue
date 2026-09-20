<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxpexwnur.css';
import '../../css/r/rpjhj7j4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":152,"height":152};
const content = `<path class="fxpexwnur"/><path class="rpjhj7j4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:todoist" /></template>
