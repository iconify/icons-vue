<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/u/u-wsh989r.css';
import '../../css/o/ozd7kohpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g class="to-5kdesz"><path class="u-wsh989r"/><path class="ozd7kohpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:nuxtjs-outline" /></template>
