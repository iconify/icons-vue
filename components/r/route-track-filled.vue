<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cj6l2-z2h.css';
import '../../css/g/gyql7h6tw.css';
import '../../css/j/jgqlw59hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cj6l2-z2h"/><path class="gyql7h6tw"/><path class="jgqlw59hy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:route-track-filled" /></template>
