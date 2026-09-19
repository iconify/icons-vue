<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbka6eb7h.css';
import '../../css/p/piht5gbxt.css';
import '../../css/k/knkpb5bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nbka6eb7h"/><path class="piht5gbxt"/><path class="knkpb5bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:new-window-stroke-16" /></template>
