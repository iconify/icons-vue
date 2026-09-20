<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh6v09b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xh6v09b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:spacing-vertical-16" /></template>
