<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/kcg668zpi.css';
import '../../css/i/ig8gsfbeh.css';
import '../../css/e/e9olh2zok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="kcg668zpi"/><path class="ig8gsfbeh"/><path class="e9olh2zok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:nested-arrows" /></template>
