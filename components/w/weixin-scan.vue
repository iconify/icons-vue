<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rinuwhlnp.css';
import '../../css/m/my44ckkmr.css';
import '../../css/g/g1pc17epq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><path class="my44ckkmr"/><path class="g1pc17epq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:weixin-scan" /></template>
