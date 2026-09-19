<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-y4uq50q.css';
import '../../css/v/v4bg1ccwj.css';
import '../../css/z/zlnvfbcfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-y4uq50q"/><path class="v4bg1ccwj"/><path class="zlnvfbcfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rfid" /></template>
