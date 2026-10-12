<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_4bw_bzz.css';
import '../../css/i/i33fspbsl.css';
import '../../css/b/bns-mjpkf.css';
import '../../css/a/a2wenh5wd.css';
import '../../css/j/jrsejkkoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a_4bw_bzz"/><path class="i33fspbsl"/><path class="bns-mjpkf"/><path class="a2wenh5wd"/><path class="jrsejkkoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:snail-20-bold" /></template>
