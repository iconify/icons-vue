<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dvnyqw4kk.css';
import '../../css/h/hqu6vb2iv.css';
import '../../css/i/ii0i11bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dvnyqw4kk"/><path clip-rule="evenodd" class="hqu6vb2iv"/><path class="ii0i11bvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-lock-solid" /></template>
