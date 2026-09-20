<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k248bwkyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k248bwkyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:slack-outline" /></template>
