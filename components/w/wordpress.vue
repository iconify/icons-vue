<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aytj6ogee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="aytj6ogee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:wordpress" /></template>
