<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_49x_b_v.css';
import '../../css/w/wr-7e-6db.css';
import '../../css/w/wyeldhbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m_49x_b_v"/><path class="wr-7e-6db"/><path class="wyeldhbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextbeats" /></template>
