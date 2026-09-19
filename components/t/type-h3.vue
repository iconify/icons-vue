<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apie_-4pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="apie_-4pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:type-h3" /></template>
