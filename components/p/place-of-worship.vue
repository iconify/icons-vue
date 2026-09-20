<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsid3bb_h.css';
import '../../css/f/f8bx8sp2h.css';
import '../../css/k/k1i6f6bht.css';
import '../../css/y/ywf1icbof.css';
import '../../css/u/u991q3bal.css';
import '../../css/s/sas0x3gzd.css';
import '../../css/d/d_y-362hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fsid3bb_h"/><circle class="f8bx8sp2h"/><path class="k1i6f6bht"/><circle class="ywf1icbof"/><path class="u991q3bal"/><path class="sas0x3gzd"/><path class="d_y-362hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:place-of-worship" /></template>
