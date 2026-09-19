<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvilx1q3c.css';
import '../../css/r/ri_106bdd.css';
import '../../css/b/b6w1e6bkw.css';
import '../../css/t/te0_flb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="kvilx1q3c"><path class="ri_106bdd"/><path class="b6w1e6bkw"/><path class="te0_flb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:mitsubishi" /></template>
