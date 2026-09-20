<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9t_h3jeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n9t_h3jeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-triangle-right" /></template>
