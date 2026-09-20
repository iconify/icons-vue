<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul-5fu98g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ul-5fu98g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stroller" /></template>
