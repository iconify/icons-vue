<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt9nc3b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wt9nc3b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:record-keys" /></template>
