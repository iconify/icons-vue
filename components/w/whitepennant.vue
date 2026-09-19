<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxbpgacte.css';
import '../../css/k/kmp30jjka.css';
import '../../css/h/hdbm4obld.css';
import '../../css/d/dmmpmib0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cxbpgacte"/><path class="kmp30jjka"/><path class="hdbm4obld"/><path class="dmmpmib0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitepennant" /></template>
