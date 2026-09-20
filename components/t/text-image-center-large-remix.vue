<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whytibb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="whytibb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:text-image-center-large-remix" /></template>
