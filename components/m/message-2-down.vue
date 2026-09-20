<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvh3ddcnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvh3ddcnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-down" /></template>
