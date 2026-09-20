<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7656tb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n7656tb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:road-accident" /></template>
