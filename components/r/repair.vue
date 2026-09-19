<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yf5xtnrqh.css';
import '../../css/f/f45mp1b7q.css';
import '../../css/j/jfffpyiud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yf5xtnrqh"/><path class="f45mp1b7q"/><path class="jfffpyiud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:repair" /></template>
