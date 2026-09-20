<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcntbabxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tcntbabxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:mast-communication" /></template>
