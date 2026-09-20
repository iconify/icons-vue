<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd1f1ab4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kd1f1ab4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:snowflake-and-icicles" /></template>
