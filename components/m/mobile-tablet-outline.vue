<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b2j7ghxra.css';
import '../../css/a/at_ainn6c.css';
import '../../css/o/or_2qzl_r.css';
import '../../css/c/chc7kx78o.css';
import '../../css/m/m704azxzk.css';
import '../../css/h/h4fpticvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b2j7ghxra"/><path clip-rule="evenodd" class="at_ainn6c"/><path clip-rule="evenodd" class="or_2qzl_r"/><path class="chc7kx78o"/><path clip-rule="evenodd" class="m704azxzk"/><path clip-rule="evenodd" class="h4fpticvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mobile-tablet-outline" /></template>
