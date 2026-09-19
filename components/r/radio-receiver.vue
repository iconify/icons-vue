<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/w_s19rzwj.css';
import '../../css/p/p91u5peyy.css';
import '../../css/k/kkh7sievk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="w_s19rzwj"/><path class="p91u5peyy"/><path class="kkh7sievk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:radio-receiver" /></template>
