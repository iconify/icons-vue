<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzky99b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gzky99b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:paragraph-unfold" /></template>
