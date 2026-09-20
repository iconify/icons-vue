<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7hstbmu.css';
import '../../css/d/dcqdxh5zc.css';
import '../../css/s/sgor8wbzm.css';
import '../../css/n/n8lxffbkh.css';
import '../../css/l/lt4p4-b0l.css';
import '../../css/c/caqr-9fws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><g class="dcqdxh5zc"><circle class="sgor8wbzm"/><path class="n8lxffbkh"/><path class="lt4p4-b0l"/><path class="caqr-9fws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:relieved-face" /></template>
