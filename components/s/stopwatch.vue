<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrrw0tgug.css';
import '../../css/k/kh_vbgbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="rrrw0tgug"/><path class="kh_vbgbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:stopwatch" /></template>
