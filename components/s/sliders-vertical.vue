<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxjng8bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lxjng8bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:sliders-vertical" /></template>
