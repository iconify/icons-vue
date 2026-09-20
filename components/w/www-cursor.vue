<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9z2gwbot.css';
import '../../css/c/czgjawueq.css';
import '../../css/g/gbe5vwbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9z2gwbot"/><path class="czgjawueq"/><path clip-rule="evenodd" class="gbe5vwbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:www-cursor" /></template>
