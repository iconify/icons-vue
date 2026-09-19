<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfsiw919t.css';
import '../../css/k/kqtvm-g_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfsiw919t"/><path class="kqtvm-g_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-exclude-alt" /></template>
