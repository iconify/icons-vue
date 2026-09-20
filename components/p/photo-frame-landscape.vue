<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shhnvhbjh.css';
import '../../css/d/duhqzbmzv.css';
import '../../css/w/wsw23sbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shhnvhbjh"/><path class="duhqzbmzv"/><path class="wsw23sbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:photo-frame-landscape" /></template>
