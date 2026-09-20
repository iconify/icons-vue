<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwh7xgb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwh7xgb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailcow-light" /></template>
