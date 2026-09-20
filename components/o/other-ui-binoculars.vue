<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7dlj0bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u7dlj0bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-binoculars" /></template>
