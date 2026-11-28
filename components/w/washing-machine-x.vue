<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf8c-4gvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf8c-4gvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:washing-machine-x" /></template>
