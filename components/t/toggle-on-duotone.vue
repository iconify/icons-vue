<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ib5-75bck.css';
import '../../css/n/n3zf9obkq.css';
import '../../css/a/ad2a0hb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ib5-75bck"/><path class="n3zf9obkq"/><path class="ad2a0hb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:toggle-on-duotone" /></template>
