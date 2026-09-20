<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkxvm8-6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wkxvm8-6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:sandbox" /></template>
