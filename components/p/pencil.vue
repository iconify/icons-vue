<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wozebsbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":695,"height":717};
const content = `<path class="wozebsbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:pencil" /></template>
