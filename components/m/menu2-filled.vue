<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1ag7wbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y1ag7wbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:menu2-filled" /></template>
