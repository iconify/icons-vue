<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/g/g9ymsib5c.css';
import '../../css/b/b3sm3p68z.css';
import '../../css/i/iycs7wjzl.css';
import '../../css/t/tsi5nvbml.css';
import '../../css/l/lisx4xbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="g9ymsib5c"/><path class="b3sm3p68z wm-shine"/><path class="iycs7wjzl wm-k"/><path class="tsi5nvbml wm-a"/><path class="lisx4xbvx wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:mushroom" /></template>
