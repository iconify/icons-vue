<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb0x8rwwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb0x8rwwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:undo" /></template>
