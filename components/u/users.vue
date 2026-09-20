<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pcyfrjbuz.css';
import '../../css/p/poeibnbcs.css';
import '../../css/a/a2caqccpk.css';
import '../../css/q/qg8wpjbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pcyfrjbuz"/><path class="poeibnbcs"/><path clip-rule="evenodd" class="a2caqccpk"/><path class="qg8wpjbhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:users" /></template>
