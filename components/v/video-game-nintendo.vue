<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i4a6ybbry.css';
import '../../css/q/qi6yf8o1f.css';
import '../../css/n/nzz56f8ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="i4a6ybbry"/><path class="qi6yf8o1f"/><path class="nzz56f8ie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:video-game-nintendo" /></template>
