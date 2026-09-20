<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5d9xcp3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t5d9xcp3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:paifang" /></template>
