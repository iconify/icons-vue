<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao25eccbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ao25eccbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:refresh" /></template>
