<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgymii1sy.css';
import '../../css/d/dllvb5bsq.css';
import '../../css/b/b9oqg8i1m.css';
import '../../css/j/jl42w1bqo.css';
import '../../css/x/xeb0reb0e.css';
import '../../css/u/u878i0b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGojMVVbVb" x1="-.102" x2="64.053" y1="32" y2="32" gradientTransform="translate(0 44.056)scale(.4913)" gradientUnits="userSpaceOnUse"><stop class="vgymii1sy"/><stop offset=".97" class="dllvb5bsq"/></linearGradient></defs><path clip-rule="evenodd" class="b9oqg8i1m"/><path fill="url(#SVGojMVVbVb)" class="jl42w1bqo"/><path class="xeb0reb0e"/><path class="u878i0b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:youtrack-wordmark" /></template>
