<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aozly20xf.css';
import '../../css/i/iikmdob_i.css';
import '../../css/u/une91ij6o.css';
import '../../css/n/nbag8d71d.css';
import '../../css/z/zer8ib_bm.css';
import '../../css/q/qvmixkwgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aozly20xf wm-shadow"/><path class="iikmdob_i wm-k"/><path class="une91ij6o wm-k"/><path class="nbag8d71d wm-k"/><path class="wm-k zer8ib_bm"/><path class="qvmixkwgv wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:trending-down" /></template>
