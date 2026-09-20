<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtpeb-edw.css';
import '../../css/m/mvq51vbwo.css';
import '../../css/g/g9s0194oq.css';
import '../../css/v/v_2s9cb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="mvq51vbwo"/><path class="g9s0194oq"/></g><path clip-rule="evenodd" class="v_2s9cb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pix-duotone" /></template>
