<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3-by5b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a3-by5b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-line-vertical" /></template>
