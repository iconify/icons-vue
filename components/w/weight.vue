<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em2nqve8q.css';
import '../../css/n/n5k9wlmuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="em2nqve8q"/><path class="n5k9wlmuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:weight" /></template>
