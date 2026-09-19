<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knc4mgb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="knc4mgb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrap-left-fill-12" /></template>
