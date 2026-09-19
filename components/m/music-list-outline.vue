<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aw2x8uv0r.css';
import '../../css/n/n35lynbiq.css';
import '../../css/q/q31b4pb4t.css';
import '../../css/g/g68vp-b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="aw2x8uv0r"/><path class="n35lynbiq"/><path clip-rule="evenodd" class="q31b4pb4t"/><path class="g68vp-b3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:music-list-outline" /></template>
