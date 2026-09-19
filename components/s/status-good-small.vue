<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voayclbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="voayclbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:status-good-small" /></template>
