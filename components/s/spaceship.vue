<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/ljakav41z.css';
import '../../css/g/gplkv5ukx.css';
import '../../css/y/yf-u9nb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ljakav41z"/><path class="gplkv5ukx"/><path class="yf-u9nb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:spaceship" /></template>
