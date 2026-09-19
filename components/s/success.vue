<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/l/lcz-itbyl.css';
import '../../css/e/el_008dkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><path class="lcz-itbyl"/><path class="el_008dkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:success" /></template>
