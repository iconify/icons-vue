<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s02addbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s02addbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:vm-connect" /></template>
