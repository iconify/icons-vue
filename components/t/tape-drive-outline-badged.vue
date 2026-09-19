<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liq-m1brr.css';
import '../../css/l/leog74bne.css';
import '../../css/u/u03d60_zk.css';
import '../../css/l/lmf0ecbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="liq-m1brr"/><path class="leog74bne"/><path class="u03d60_zk"/><circle class="lmf0ecbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tape-drive-outline-badged" /></template>
