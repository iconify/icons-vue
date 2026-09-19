<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psh9t9-yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="psh9t9-yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-bars-vertical" /></template>
