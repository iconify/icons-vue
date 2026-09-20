<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jthl_nb3l.css';
import '../../css/p/pe8tb_8ds.css';
import '../../css/r/rk2bd1jzl.css';
import '../../css/w/wvsq8lpvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jthl_nb3l"/><path class="pe8tb_8ds"/><path class="rk2bd1jzl"/><path class="wvsq8lpvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:show-theater-drama-1" /></template>
