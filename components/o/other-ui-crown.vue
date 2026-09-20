<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs5l0aben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fs5l0aben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-crown" /></template>
