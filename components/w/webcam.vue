<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uou8spbqk.css';
import '../../css/y/y306aceyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uou8spbqk"/><path class="y306aceyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:webcam" /></template>
