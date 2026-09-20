<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfe-tv.css';
import '../../css/s/s8e22g.css';
import '../../css/z/z5tiej.css';
import '../../css/d/d-vg0s0b.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfe-tv s8e22g"/><path class="s8e22g z5tiej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:patreon" /></template>
