<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av8ob7b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="av8ob7b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:volume-outline" /></template>
