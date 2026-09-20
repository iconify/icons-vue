<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajvc1_b-l.css';
import '../../css/u/unwic5qnb.css';
import '../../css/b/bj2guyupp.css';
import '../../css/j/jqdg6w_dd.css';
import '../../css/d/dttu61bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ajvc1_b-l"/><path class="unwic5qnb"/><path class="bj2guyupp"/><path class="jqdg6w_dd"/><path class="dttu61bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wiki-js-light" /></template>
