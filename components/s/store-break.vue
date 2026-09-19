<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pbwszacym.css';
import '../../css/s/s1uxt9bdb.css';
import '../../css/p/pm9h7pbes.css';
import '../../css/q/qd6ov3byx.css';
import '../../css/b/b7p5azb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="pbwszacym"/><path class="s1uxt9bdb"/><path class="pm9h7pbes"/><path clip-rule="evenodd" class="qd6ov3byx"/><path class="b7p5azb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:store-break" /></template>
