<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2u665ban.css';
import '../../css/p/py7ktqbvf.css';
import '../../css/c/cardt04wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="py7ktqbvf"/><path class="cardt04wx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:snapchat" /></template>
