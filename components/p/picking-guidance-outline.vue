<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar_uynbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ar_uynbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:picking-guidance-outline" /></template>
