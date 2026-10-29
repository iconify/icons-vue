<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy-spkb2y.css';
import '../../css/w/wjdew_bmk.css';
import '../../css/l/lzs-5qbmk.css';
import '../../css/t/t-tofxbnm.css';
import '../../css/q/q9saabcpl.css';
import '../../css/q/qmt27qbnx.css';
import '../../css/l/lffja4b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy-spkb2y wm-shadow"/><path class="wjdew_bmk"/><path class="lzs-5qbmk"/><path class="t-tofxbnm"/><path class="q9saabcpl"/><path class="qmt27qbnx wm-shine"/><path class="lffja4b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:triangle" /></template>
