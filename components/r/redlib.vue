<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqu2_e4mu.css';
import '../../css/i/i-02_nl2g.css';
import '../../css/e/eyc-0ib3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="pqu2_e4mu"/><path class="i-02_nl2g"/><path class="eyc-0ib3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:redlib" /></template>
