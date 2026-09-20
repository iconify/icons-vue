<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lq7a-_8su.css';
import '../../css/v/vq44mp76d.css';
import '../../css/a/a0gtrrbuj.css';
import '../../css/m/m38jkydoe.css';
import '../../css/j/j3e3yponk.css';
import '../../css/k/kq_hv7btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lq7a-_8su"/><path class="vq44mp76d"/><path class="a0gtrrbuj"/><path class="m38jkydoe"/><path class="j3e3yponk"/><path class="kq_hv7btj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signpost-broken" /></template>
