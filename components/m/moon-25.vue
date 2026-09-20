<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkx3sqbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="bkx3sqbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-25" /></template>
