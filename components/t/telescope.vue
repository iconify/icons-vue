<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn8m7vbib.css';
import '../../css/o/o9_qvlbwy.css';
import '../../css/c/cwmeeibwc.css';
import '../../css/c/c1mz_9byp.css';
import '../../css/p/pv9xaozvi.css';
import '../../css/p/pinmuxbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="rn8m7vbib"/><path class="o9_qvlbwy"/><path class="cwmeeibwc"/><path class="c1mz_9byp"/><circle class="pv9xaozvi"/><path class="pinmuxbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:telescope" /></template>
