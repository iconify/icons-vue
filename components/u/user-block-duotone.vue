<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h9kqrfbgx.css';
import '../../css/i/iof_a_26r.css';
import '../../css/x/xs_sbwbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h9kqrfbgx"/><path clip-rule="evenodd" class="iof_a_26r"/><path class="xs_sbwbww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-block-duotone" /></template>
