<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e76ndrbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":504,"height":400};
const content = `<path class="e76ndrbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wifi" /></template>
