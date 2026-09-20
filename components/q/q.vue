<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbf2j5b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wbf2j5b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:q" /></template>
