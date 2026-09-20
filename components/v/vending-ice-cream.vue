<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg5u6gbbk.css';
import '../../css/b/b3b6v3bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xg5u6gbbk"/><path class="b3b6v3bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:vending-ice-cream" /></template>
