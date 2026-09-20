<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_kh_l8jn.css';
import '../../css/k/kekxfrtgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_kh_l8jn"/><path class="kekxfrtgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shuthost" /></template>
