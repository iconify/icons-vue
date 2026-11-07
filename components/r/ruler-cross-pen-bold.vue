<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py1haibyr.css';
import '../../css/r/rl670hs1g.css';
import '../../css/f/f-98sr1ba.css';
import '../../css/y/y608-6bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py1haibyr"/><path class="rl670hs1g"/><path class="f-98sr1ba"/><path class="y608-6bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-cross-pen-bold" /></template>
