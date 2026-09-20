<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7b-_ybbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d7b-_ybbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:volume-2-outline" /></template>
