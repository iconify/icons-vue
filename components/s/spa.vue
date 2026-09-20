<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byiz0jbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="byiz0jbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:spa" /></template>
