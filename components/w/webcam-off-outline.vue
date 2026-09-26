<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h6yptrb_l.css';
import '../../css/v/vlmyf2b8p.css';
import '../../css/s/st8kcmusv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h6yptrb_l"/><path clip-rule="evenodd" class="vlmyf2b8p"/><path class="st8kcmusv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-off-outline" /></template>
