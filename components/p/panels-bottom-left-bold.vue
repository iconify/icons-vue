<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d2lm5bc3q.css';
import '../../css/u/udc6961nl.css';
import '../../css/y/ye1fytb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d2lm5bc3q"/><path class="udc6961nl"/><path clip-rule="evenodd" class="ye1fytb6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-left-bold" /></template>
