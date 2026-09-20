<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxwr-bxls.css';
import '../../css/c/citlv-btt.css';
import '../../css/q/qpac77bkh.css';
import '../../css/j/jidhs7d5l.css';
import '../../css/n/nn93icb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxwr-bxls"/><path class="citlv-btt"/><path class="qpac77bkh"/><path class="jidhs7d5l"/><path class="nn93icb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:vk-alt" /></template>
