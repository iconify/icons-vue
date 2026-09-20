<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb_p7iblt.css';
import '../../css/j/jmf7y0dun.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/h/h557o4b_c.css';
import '../../css/o/o9afzxb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tb_p7iblt"/><path class="jmf7y0dun"/><g class="jn8qy4bru"><path class="h557o4b_c"/><path class="o9afzxb_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:violin" /></template>
