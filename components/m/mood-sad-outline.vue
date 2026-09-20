<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtt0f29xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mtt0f29xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-sad-outline" /></template>
