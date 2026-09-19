<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lk0f4vb0h.css';
import '../../css/j/jbgc_pbkv.css';
import '../../css/z/zy2inmb_d.css';
import '../../css/i/ivbd4mb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lk0f4vb0h"/><path class="jbgc_pbkv"/><path class="zy2inmb_d"/><path class="ivbd4mb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:microphone" /></template>
