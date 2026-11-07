<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syolcfb-b.css';
import '../../css/z/zze6oyfyz.css';
import '../../css/q/qne0ekbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="syolcfb-b"/><path class="zze6oyfyz"/><path class="qne0ekbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:socket-outline" /></template>
