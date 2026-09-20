<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0konbola.css';
import '../../css/h/hh_xii4of.css';
import '../../css/j/j_9iofr5v.css';
import '../../css/v/vqk-zqyzu.css';
import '../../css/v/vp7zkm-il.css';
import '../../css/f/f0af7x_ye.css';
import '../../css/f/f40n46bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGjzCQKbkG" x1="256" x2="256" y1="499.629" y2="12.371" gradientUnits="userSpaceOnUse"><stop offset="0" class="f0konbola"/><stop offset=".182" class="hh_xii4of"/><stop offset=".397" class="j_9iofr5v"/><stop offset=".627" class="vqk-zqyzu"/><stop offset=".868" class="vp7zkm-il"/><stop offset="1" class="f0af7x_ye"/></linearGradient><path fill="url(#SVGjzCQKbkG)" class="f40n46bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:soulseek" /></template>
