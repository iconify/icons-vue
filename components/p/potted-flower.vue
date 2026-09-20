<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nog59-bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nog59-bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:potted-flower" /></template>
