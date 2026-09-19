<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guts1yb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="guts1yb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:switch" /></template>
