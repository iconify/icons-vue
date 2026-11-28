<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r49p3zgbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r49p3zgbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tag-plus" /></template>
