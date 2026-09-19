<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grjom1bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grjom1bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:play-track-next" /></template>
