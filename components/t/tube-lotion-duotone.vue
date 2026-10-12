<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s31bbjq4l.css';
import '../../css/f/ffsrxocry.css';
import '../../css/a/a-qr3fefb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s31bbjq4l"/><path class="ffsrxocry"/><path class="a-qr3fefb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tube-lotion-duotone" /></template>
