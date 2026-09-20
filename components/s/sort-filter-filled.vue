<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcw0y79um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wcw0y79um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:sort-filter-filled" /></template>
