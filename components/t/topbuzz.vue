<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a03qbvbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a03qbvbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:topbuzz" /></template>
