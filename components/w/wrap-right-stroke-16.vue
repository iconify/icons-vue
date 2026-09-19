<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/popmkw-ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="popmkw-ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrap-right-stroke-16" /></template>
