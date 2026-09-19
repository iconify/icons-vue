<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-wmiybgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-wmiybgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tree-03" /></template>
