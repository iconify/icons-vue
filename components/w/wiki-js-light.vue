<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxqr4bbni.css';
import '../../css/f/f752_u1ed.css';
import '../../css/u/ungc_tbic.css';
import '../../css/j/jqdg6w_dd.css';
import '../../css/f/fdunp569o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yxqr4bbni"/><path class="f752_u1ed"/><path class="ungc_tbic"/><path class="jqdg6w_dd"/><path class="fdunp569o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wiki-js-light" /></template>
