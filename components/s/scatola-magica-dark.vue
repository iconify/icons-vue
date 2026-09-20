<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9bllgb-i.css';
import '../../css/s/sbfj-0zmi.css';
import '../../css/j/jh6xwxbpv.css';
import '../../css/w/wv69ft2op.css';
import '../../css/d/dp94l_bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9bllgb-i"/><path class="sbfj-0zmi"/><path class="jh6xwxbpv"/><path class="wv69ft2op"/><path class="dp94l_bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scatola-magica-dark" /></template>
