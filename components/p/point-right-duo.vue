<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp71tt-6y.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r9dhqacfo.css';
import '../../css/q/qy56o9fty.css';
import '../../css/b/bbvdnfrhh.css';
import '../../css/e/etewfjb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp71tt-6y secondary"/><g class="dt0cm9dhy primary"><path class="r9dhqacfo"/><path class="qy56o9fty"/><path class="bbvdnfrhh"/><path class="etewfjb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:point-right-duo" /></template>
