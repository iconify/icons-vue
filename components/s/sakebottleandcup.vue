<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmeesubxi.css';
import '../../css/l/l08ji0b1b.css';
import '../../css/q/q8whoub3o.css';
import '../../css/b/bi6rp_ibq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rmeesubxi"/><path class="l08ji0b1b"/><path class="q8whoub3o"/><path class="bi6rp_ibq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sakebottleandcup" /></template>
