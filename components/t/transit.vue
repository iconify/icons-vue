<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0n52ulmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x0n52ulmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:transit" /></template>
