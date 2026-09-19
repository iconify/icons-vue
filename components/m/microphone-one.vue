<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/zx9s-4b6r.css';
import '../../css/c/cplpj-rbo.css';
import '../../css/i/icfu2xbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="zx9s-4b6r"/><circle class="cplpj-rbo"/><path class="icfu2xbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:microphone-one" /></template>
