<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds3f65bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ds3f65bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:volume-0" /></template>
