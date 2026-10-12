<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrff5xbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rrff5xbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:share-fill-20" /></template>
