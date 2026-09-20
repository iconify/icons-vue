<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbf53ukmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gbf53ukmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:type-16" /></template>
