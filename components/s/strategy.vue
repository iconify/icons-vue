<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zvj-_tbck.css';
import '../../css/l/lzkg2p4uu.css';
import '../../css/m/m5c3whiql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zvj-_tbck"/><circle class="lzkg2p4uu"/><path class="m5c3whiql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:strategy" /></template>
