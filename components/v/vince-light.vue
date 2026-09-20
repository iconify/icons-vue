<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug7066bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ug7066bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vince-light" /></template>
