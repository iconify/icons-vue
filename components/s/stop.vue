<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxo8xlvlz.css';
import '../../css/a/aq9dxkzst.css';
import '../../css/m/m26ufgtle.css';
import '../../css/c/ceyr7rb7x.css';
import '../../css/n/no762vjnp.css';
import '../../css/d/d010y-vrp.css';
import '../../css/m/mjp03jv2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxo8xlvlz wm-shadow"/><path class="aq9dxkzst wm-k"/><path class="m26ufgtle wm-k"/><path class="ceyr7rb7x wm-k"/><path class="no762vjnp wm-k"/><path class="d010y-vrp wm-k"/><path class="mjp03jv2u wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:stop" /></template>
