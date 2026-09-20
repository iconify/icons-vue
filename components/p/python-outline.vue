<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmi6sy-ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gmi6sy-ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:python-outline" /></template>
