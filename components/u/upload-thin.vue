<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r61xpml1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r61xpml1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:upload-thin" /></template>
