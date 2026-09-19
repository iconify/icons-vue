<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrftxpb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":895};
const content = `<path class="mrftxpb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mountains" /></template>
