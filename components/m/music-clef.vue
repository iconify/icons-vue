<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc5uqjbvk.css';
import '../../css/k/kde8vp2lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc5uqjbvk"/><path class="kde8vp2lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:music-clef" /></template>
