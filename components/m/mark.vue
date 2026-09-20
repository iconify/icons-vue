<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upg_mvemj.css';
import '../../css/s/sfy5rz71v.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/v/vt2oo7o4z.css';
import '../../css/v/vdjc6_bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="upg_mvemj"/><path class="sfy5rz71v"/><g class="jn8qy4bru"><path class="vt2oo7o4z"/><path class="vdjc6_bwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mark" /></template>
