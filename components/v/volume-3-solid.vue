<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut-ddebui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ut-ddebui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:volume-3-solid" /></template>
