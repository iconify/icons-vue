<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz-h02jqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz-h02jqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:plate" /></template>
