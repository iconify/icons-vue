<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzeez2bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzeez2bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-vertical" /></template>
