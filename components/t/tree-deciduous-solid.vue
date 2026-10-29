<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9sf339bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9sf339bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tree-deciduous-solid" /></template>
