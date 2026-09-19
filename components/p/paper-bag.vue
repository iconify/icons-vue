<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqau8zbpj.css';
import '../../css/c/cc9g64bnc.css';
import '../../css/x/xwim_abin.css';
import '../../css/d/d6yirzm0p.css';
import '../../css/f/fl816wwvr.css';
import '../../css/q/q7rzffsgz.css';
import '../../css/b/bbds41o0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="pqau8zbpj"/><path class="cc9g64bnc"/><path class="xwim_abin"/><path class="d6yirzm0p"/><circle class="fl816wwvr"/><circle class="q7rzffsgz"/><path clip-rule="evenodd" class="bbds41o0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:paper-bag" /></template>
