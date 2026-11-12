<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlbgi5b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rlbgi5b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pent-no-dark" /></template>
