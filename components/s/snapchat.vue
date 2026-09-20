<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0im_gbxt.css';
import '../../css/n/n7miu-b0l.css';
import '../../css/f/fahhi3b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v0im_gbxt"/><path class="n7miu-b0l"/><path class="fahhi3b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapchat" /></template>
