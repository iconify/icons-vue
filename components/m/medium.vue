<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxjb7dbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bxjb7dbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:medium" /></template>
