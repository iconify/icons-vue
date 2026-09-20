<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0ragzbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i0ragzbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:unlink-filled" /></template>
