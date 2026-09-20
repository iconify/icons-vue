<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s5bbu8buq.css';
import '../../css/t/tv6p83bhq.css';
import '../../css/c/c_zdt_bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s5bbu8buq"/><path clip-rule="evenodd" class="tv6p83bhq"/><path class="c_zdt_bqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-minus-bold" /></template>
