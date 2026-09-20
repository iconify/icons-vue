<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc3muq5bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lc3muq5bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:plant-outline" /></template>
