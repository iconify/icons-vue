<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lw2g2bb3f.css';
import '../../css/s/skqzgzjwd.css';
import '../../css/p/pjqa07bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lw2g2bb3f"/><path class="skqzgzjwd wm-a"/><path class="pjqa07bbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toggle-duo" /></template>
