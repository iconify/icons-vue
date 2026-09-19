<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrhbwb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bbrhbwb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:topbuzz" /></template>
