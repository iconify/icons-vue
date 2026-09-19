<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u99giob-v.css';
import '../../css/h/hrejwrbgb.css';
import '../../css/g/gba4ubbyo.css';
import '../../css/x/xk_izwn6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="u99giob-v"/><rect class="hrejwrbgb"/><rect class="gba4ubbyo"/><rect class="xk_izwn6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:menu-2-fill" /></template>
