<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lo92hvbun.css';
import '../../css/u/u4sxwwy9k.css';
import '../../css/c/cqsfoebtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="lo92hvbun"/><path class="u4sxwwy9k"/><path class="cqsfoebtm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:panel-left-right-dashed" /></template>
