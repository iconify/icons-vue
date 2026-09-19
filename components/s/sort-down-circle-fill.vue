<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzerl6y7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xzerl6y7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sort-down-circle-fill" /></template>
