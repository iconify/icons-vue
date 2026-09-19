<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt_ca-b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lt_ca-b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:text-style" /></template>
