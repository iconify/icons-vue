<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deb4nz_eq.css';
import '../../css/f/fea8sczxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b deb4nz_eq"/><path class="b fea8sczxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:whiteboard-alt" /></template>
