<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j---shb0m.css';
import '../../css/n/neea8pi3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j---shb0m"/><path class="neea8pi3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-clef-sheet" /></template>
