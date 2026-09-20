<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dls6cz9sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dls6cz9sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:tick-small-outline" /></template>
