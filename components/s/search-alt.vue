<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w03eki6yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w03eki6yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:search-alt" /></template>
