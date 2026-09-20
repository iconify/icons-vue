<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgqon1dhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgqon1dhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:play-circle-filled" /></template>
