<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3by5zb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c3by5zb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-list-ul" /></template>
