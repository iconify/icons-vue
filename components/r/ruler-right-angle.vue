<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urq73-b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="urq73-b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:ruler-right-angle" /></template>
