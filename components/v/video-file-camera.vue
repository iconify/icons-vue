<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opnjybc5u.css';
import '../../css/a/afp1jxb0a.css';
import '../../css/k/klb71kbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opnjybc5u"/><path class="afp1jxb0a"/><path clip-rule="evenodd" class="klb71kbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:video-file-camera" /></template>
