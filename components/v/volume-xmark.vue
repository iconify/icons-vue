<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1o6-hbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e1o6-hbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:volume-xmark" /></template>
