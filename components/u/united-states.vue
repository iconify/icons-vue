<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmibc4bxr.css';
import '../../css/d/dkr5qebiv.css';
import '../../css/p/pb_xy5vyx.css';
import '../../css/d/dohuy7b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="dkr5qebiv"/><path class="pb_xy5vyx"/><path class="dohuy7b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:united-states" /></template>
