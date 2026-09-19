<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwiky-9zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mwiky-9zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:rectangles-4" /></template>
