<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/l/l0bn-3b4l.css';
import '../../css/g/gdadi8r8p.css';
import '../../css/k/kq90zdiwo.css';
import '../../css/s/sh8jsqb_h.css';
import '../../css/n/nn82nnb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><g class="l0bn-3b4l"><path class="gdadi8r8p"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.6s" values="56;0"/></path><path stroke-dashoffset="8" class="kq90zdiwo"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.6s" dur="0.2s" to="0"/></path></g><path stroke-dashoffset="8" class="sh8jsqb_h"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.8s" dur="0.2s" to="0"/></path></g><path fill-opacity="0" class="nn82nnb0w"><animate fill="freeze" attributeName="fill-opacity" begin="1s" dur="0.15s" to=".3"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:pencil-twotone-alt" /></template>
