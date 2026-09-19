<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/p/p71cm1b1k.css';
import '../../css/e/e3pn2bxuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="p71cm1b1k"/><path class="e3pn2bxuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:setting-one" /></template>
