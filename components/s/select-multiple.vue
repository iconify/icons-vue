<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4h-6kbxp.css';
import '../../css/o/ooxjw-29z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4h-6kbxp"/><path class="ooxjw-29z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:select-multiple" /></template>
