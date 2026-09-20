<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq_64wqcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hq_64wqcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ripple-outline" /></template>
