<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqbs--b0w.css';
import '../../css/u/uoax7obne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqbs--b0w"/><path clip-rule="evenodd" class="uoax7obne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:remote-controller-2-bold" /></template>
