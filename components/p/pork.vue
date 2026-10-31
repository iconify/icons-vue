<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqmbunszu.css';
import '../../css/t/tyh7i7bjl.css';
import '../../css/l/l059qz18g.css';
import '../../css/c/ch1179b3s.css';
import '../../css/n/nfxloigqf.css';
import '../../css/w/wq2oayscy.css';
import '../../css/q/qcibju32j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rqmbunszu"/><path class="tyh7i7bjl"/><path class="l059qz18g"/><path class="ch1179b3s"/><path class="nfxloigqf"/><path class="wq2oayscy"/><path class="qcibju32j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:pork" /></template>
