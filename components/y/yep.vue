<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1b0wqoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iw1b0wqoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:yep" /></template>
