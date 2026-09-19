<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbr48rber.css';
import '../../css/n/neglx700n.css';
import '../../css/r/raaz8qbsm.css';
import '../../css/v/vueepbcbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbr48rber"/><path class="neglx700n"/><path class="raaz8qbsm"/><path class="vueepbcbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:volume-binding-outlined" /></template>
