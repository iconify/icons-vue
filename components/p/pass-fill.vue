<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtn--hnvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xtn--hnvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pass-fill" /></template>
