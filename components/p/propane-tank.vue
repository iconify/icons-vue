<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5s_hac7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x5s_hac7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:propane-tank" /></template>
