<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q8f9jxbbr.css';
import '../../css/l/lnrengbdk.css';
import '../../css/q/qyqyr9byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="q8f9jxbbr"/><path class="lnrengbdk"/><rect class="qyqyr9byk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:tv" /></template>
