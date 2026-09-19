<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0z4jk4ef.css';
import '../../css/d/dbsjb5b_u.css';
import '../../css/l/lzvh4scbg.css';
import '../../css/c/cd3dpacbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="s0z4jk4ef"/><path class="dbsjb5b_u"/><path class="lzvh4scbg"/><path class="cd3dpacbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:ringingbell" /></template>
