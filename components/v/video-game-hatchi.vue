<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/aroz0npjy.css';
import '../../css/e/ec32yhb6f.css';
import '../../css/l/l45dc9b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="aroz0npjy"/><path class="ec32yhb6f"/><path class="l45dc9b6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:video-game-hatchi" /></template>
