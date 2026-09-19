<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j7kn5jb8z.css';
import '../../css/b/bz49hkbpc.css';
import '../../css/n/n3_7dmu3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="j7kn5jb8z"/><path class="bz49hkbpc"/><circle class="n3_7dmu3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:whale" /></template>
