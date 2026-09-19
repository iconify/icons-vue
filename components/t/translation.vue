<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip7fo_bgm.css';
import '../../css/d/db48s2fzd.css';
import '../../css/t/trzudzbao.css';
import '../../css/r/r97ruqj2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ip7fo_bgm"/><path class="db48s2fzd duoicon-primary-layer"/><path class="duoicon-secondary-layer trzudzbao"/><path class="duoicon-primary-layer r97ruqj2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:translation" /></template>
