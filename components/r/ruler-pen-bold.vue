<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rgdufzqdj.css';
import '../../css/t/t8ykyt4yk.css';
import '../../css/w/wcj52rb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rgdufzqdj"/><path class="t8ykyt4yk"/><path class="wcj52rb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-pen-bold" /></template>
