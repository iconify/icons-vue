<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qc_d--bcm.css';
import '../../css/l/lmcg74bhh.css';
import '../../css/t/t12n55-xl.css';
import '../../css/r/rt044bc1h.css';
import '../../css/b/b_vlnrdwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qc_d--bcm"/><path class="lmcg74bhh"/><path class="t12n55-xl"/><path class="rt044bc1h"/><path class="b_vlnrdwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:mouse" /></template>
