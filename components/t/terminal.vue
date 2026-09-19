<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/p/p4anfmj7x.css';
import '../../css/b/b0bz2xbyx.css';
import '../../css/k/kr7u95b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="p4anfmj7x"/><path class="b0bz2xbyx"/><path class="kr7u95b8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:terminal" /></template>
