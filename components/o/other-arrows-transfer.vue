<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t94-lt9lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t94-lt9lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-arrows-transfer" /></template>
