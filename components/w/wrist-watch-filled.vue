<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj0x1lb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj0x1lb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wrist-watch-filled" /></template>
