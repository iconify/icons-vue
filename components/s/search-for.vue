<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bck2uobie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="bck2uobie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:search-for" /></template>
