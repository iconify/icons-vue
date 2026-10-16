<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjj-1pc-n.css';
import '../../css/y/ynpxxgbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xjj-1pc-n"/><path class="ynpxxgbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mailbox-20-bold" /></template>
