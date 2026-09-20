<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s8y023b0u.css';
import '../../css/p/pknklcb3b.css';
import '../../css/t/tqfsqjbfu.css';
import '../../css/m/muvu13hjo.css';
import '../../css/n/n-y7-h-tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s8y023b0u"/><path class="pknklcb3b"/><path class="tqfsqjbfu"/><path class="muvu13hjo"/><path class="n-y7-h-tz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-track-broken" /></template>
