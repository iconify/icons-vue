<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_16pexbl.css';
import '../../css/x/xy0ygzbmk.css';
import '../../css/q/qlv67_b1g.css';
import '../../css/a/aw6d82lyt.css';
import '../../css/i/iq7o9449n.css';
import '../../css/e/e_91tzb5p.css';
import '../../css/f/fwlu77bge.css';
import '../../css/y/yf933-bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="r_16pexbl"/><path class="xy0ygzbmk"/><path class="qlv67_b1g"/><path class="aw6d82lyt"/><path class="iq7o9449n"/><circle class="e_91tzb5p"/><circle class="fwlu77bge"/><path class="yf933-bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:moose" /></template>
