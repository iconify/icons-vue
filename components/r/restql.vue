<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywimt5b1o.css';
import '../../css/c/cyo4yw9bp.css';
import '../../css/w/wv2mlgdyl.css';
import '../../css/n/niphly_2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="ywimt5b1o"/><path class="cyo4yw9bp"/><path class="wv2mlgdyl"/><path class="niphly_2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:restql" /></template>
