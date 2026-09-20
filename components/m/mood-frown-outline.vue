<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7ub_xb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u7ub_xb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-frown-outline" /></template>
