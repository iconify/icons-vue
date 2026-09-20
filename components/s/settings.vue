<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmg9kobid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kmg9kobid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:settings" /></template>
