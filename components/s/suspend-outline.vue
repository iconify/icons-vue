<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyozvw1iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nyozvw1iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:suspend-outline" /></template>
