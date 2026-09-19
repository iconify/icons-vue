<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sgex78bhw.css';
import '../../css/p/pjance51f.css';
import '../../css/h/hvy19cb7c.css';
import '../../css/r/r_0yv_v8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="notification-bell-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="sgex78bhw"/><path clip-rule="evenodd" class="pjance51f"/><path class="hvy19cb7c"/><path clip-rule="evenodd" class="r_0yv_v8w"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:notification-bell-outline" /></template>
