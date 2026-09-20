<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4i2n-v3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v4i2n-v3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tree-and-bench" /></template>
