<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue2-q7bvs.css';
import '../../css/o/omzwhtckx.css';
import '../../css/y/ykxzx4ykb.css';
import '../../css/o/o44rtxuym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue2-q7bvs"/><path class="omzwhtckx"/><path class="ykxzx4ykb"/><path clip-rule="evenodd" class="o44rtxuym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-3-bold-duotone" /></template>
