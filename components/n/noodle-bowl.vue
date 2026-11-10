<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i73l00gnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i73l00gnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:noodle-bowl" /></template>
