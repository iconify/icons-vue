<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/q/qtqj_t.css';
import '../../css/u/uw82ng.css';
import '../../css/r/ricadr.css';
import '../../css/r/rqdeuu.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c qtqj_t"/><path class="a0m25c uw82ng"/><path class="a0m25c ricadr"/><path class="a0m25c rqdeuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:menu-unfold-right" /></template>
