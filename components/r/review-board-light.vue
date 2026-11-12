<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkv6y8nxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gkv6y8nxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:review-board-light" /></template>
