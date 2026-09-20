<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhkq8cbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bhkq8cbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-gasoline-pump" /></template>
