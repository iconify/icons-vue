<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-n2__egq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r-n2__egq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-method" /></template>
