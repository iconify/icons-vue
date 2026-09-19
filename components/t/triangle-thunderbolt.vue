<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beko8jbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="beko8jbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:triangle-thunderbolt" /></template>
