<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t7mv73bbb.css';
import '../../css/i/izhj-bbzf.css';
import '../../css/v/v8fo5bcui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t7mv73bbb"/><path class="izhj-bbzf"/><path class="v8fo5bcui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:picture-in-picture-exit" /></template>
