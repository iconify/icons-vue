<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmn_z5chk.css';
import '../../css/p/pn2j6edzu.css';
import '../../css/f/fh6l5_iwg.css';
import '../../css/x/x6dmml5yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fmn_z5chk"/><path class="pn2j6edzu"/><path class="fh6l5_iwg"/><path class="x6dmml5yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-rig-20-bold" /></template>
