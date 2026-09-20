<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it6_3nsgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="it6_3nsgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:sort-a-to-z-outline" /></template>
