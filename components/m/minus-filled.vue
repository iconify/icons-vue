<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svq43ibny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="svq43ibny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:minus-filled" /></template>
