<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/fmeovypeb.css';
import '../../css/k/kjeii5b8e.css';
import '../../css/l/lrd4lfbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fmeovypeb"/><path class="kjeii5b8e"/><path class="lrd4lfbqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:qwen" /></template>
