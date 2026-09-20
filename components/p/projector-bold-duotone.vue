<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i04qd9myb.css';
import '../../css/h/hmxp7xylf.css';
import '../../css/l/l0durob0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i04qd9myb"/><path class="hmxp7xylf"/><path class="l0durob0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:projector-bold-duotone" /></template>
