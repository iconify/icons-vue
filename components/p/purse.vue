<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v_r5ykbmt.css';
import '../../css/g/g2ony-pew.css';
import '../../css/r/rk9rf7bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="v_r5ykbmt"/><path class="g2ony-pew"/><path class="rk9rf7bhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:purse" /></template>
