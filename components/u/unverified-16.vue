<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s87_q_bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s87_q_bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unverified-16" /></template>
