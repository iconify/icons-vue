<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/c3-vr29xh.css';
import '../../css/b/bixa75bad.css';
import '../../css/o/ou8i0etgx.css';
import '../../css/k/kyx_bcc0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="c3-vr29xh"/><path class="bixa75bad"/><path class="ou8i0etgx"/><path class="kyx_bcc0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:video-game-mario-mushroom-1" /></template>
