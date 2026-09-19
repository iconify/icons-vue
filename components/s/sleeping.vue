<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tecf02bgm.css';
import '../../css/i/iay28bc3j.css';
import '../../css/b/b4k3pebzr.css';
import '../../css/g/g8tn2v2pu.css';
import '../../css/q/qqgrn5b-m.css';
import '../../css/s/sv08iqzqu.css';
import '../../css/p/p1iw5mbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tecf02bgm"/><path class="iay28bc3j"/><path class="b4k3pebzr"/><path class="g8tn2v2pu"/><path class="qqgrn5b-m"/><path class="sv08iqzqu"/><path class="p1iw5mbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sleeping" /></template>
