<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuz9-1bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fuz9-1bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-forms-2016-dark" /></template>
