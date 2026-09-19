<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/u3p9f6bio.css';
import '../../css/v/vzydv6hlq.css';
import '../../css/k/kym7xq7br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="u3p9f6bio"/><circle transform="rotate(-90 37 8.944)" class="vzydv6hlq"/><path class="kym7xq7br"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:split-turn-down-left" /></template>
