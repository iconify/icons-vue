<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pw9cfbbav.css';
import '../../css/p/p1dkmfbom.css';
import '../../css/g/gh1dxtbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pw9cfbbav"/><path class="p1dkmfbom"/><path clip-rule="evenodd" class="gh1dxtbmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:thumbtack-list-filled" /></template>
