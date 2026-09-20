<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6ost54tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x6ost54tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:oclock-outline" /></template>
