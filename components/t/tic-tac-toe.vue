<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hkjgs7b4v.css';
import '../../css/y/ys41-gbgp.css';
import '../../css/z/z0bu-ib7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hkjgs7b4v"/><path class="ys41-gbgp"/><path class="z0bu-ib7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tic-tac-toe" /></template>
