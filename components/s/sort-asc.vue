<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bweij_vym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bweij_vym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort-asc" /></template>
