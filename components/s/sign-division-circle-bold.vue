<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/s/s_24sns7n.css';
import '../../css/y/ys1gjwbls.css';
import '../../css/y/yt9q-fb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><circle class="s_24sns7n"/><path class="ys1gjwbls"/><path class="yt9q-fb4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-division-circle-bold" /></template>
