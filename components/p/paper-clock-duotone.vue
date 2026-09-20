<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/p1nehyewa.css';
import '../../css/q/qe1p392fw.css';
import '../../css/e/e5d74-yqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="p1nehyewa"/><path class="qe1p392fw"/><path class="e5d74-yqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:paper-clock-duotone" /></template>
