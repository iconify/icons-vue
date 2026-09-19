<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzv6z5blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qzv6z5blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-backward-btn-fill" /></template>
