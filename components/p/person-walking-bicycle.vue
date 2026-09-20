<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmdn0hbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xmdn0hbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-bicycle" /></template>
