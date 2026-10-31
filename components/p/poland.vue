<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arptzobve.css';
import '../../css/x/xomdi8b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="arptzobve"/><path class="xomdi8b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:poland" /></template>
