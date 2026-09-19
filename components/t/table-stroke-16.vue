<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_z31w16g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t_z31w16g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:table-stroke-16" /></template>
