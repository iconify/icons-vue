<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9b2o80qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d9b2o80qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:sticker" /></template>
