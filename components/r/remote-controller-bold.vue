<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqbs--b0w.css';
import '../../css/b/bgpl6nb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqbs--b0w"/><path clip-rule="evenodd" class="bgpl6nb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:remote-controller-bold" /></template>
