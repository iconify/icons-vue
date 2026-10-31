<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tps0pable.css';
import '../../css/l/lrkc4ubzw.css';
import '../../css/s/sgl_4_kwk.css';
import '../../css/t/tbw07rbmi.css';
import '../../css/h/ho9l-mb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="tps0pable"/><path class="lrkc4ubzw"/><path class="sgl_4_kwk"/><path class="tbw07rbmi"/><path class="ho9l-mb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:potato" /></template>
