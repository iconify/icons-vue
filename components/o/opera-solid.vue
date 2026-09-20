<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw82a8b6o.css';
import '../../css/u/u048i3bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fw82a8b6o"/><path class="u048i3bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:opera-solid" /></template>
