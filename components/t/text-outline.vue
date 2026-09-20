<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldhof1blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ldhof1blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:text-outline" /></template>
