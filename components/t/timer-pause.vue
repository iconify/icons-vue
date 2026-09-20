<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hoqg9vbdg.css';
import '../../css/k/ke7d84ibd.css';
import '../../css/w/wq2wc4bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hoqg9vbdg"/><path class="ke7d84ibd"/><path class="wq2wc4bco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:timer-pause" /></template>
