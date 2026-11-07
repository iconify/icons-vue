<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_medy5gw.css';
import '../../css/w/wd_9hbcol.css';
import '../../css/w/woowbybcs.css';
import '../../css/w/wv0hdzbhs.css';
import '../../css/t/tv1xwfcle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_medy5gw"/><path class="wd_9hbcol"/><path class="woowbybcs"/><path class="wv0hdzbhs"/><path class="tv1xwfcle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-cross-bold" /></template>
