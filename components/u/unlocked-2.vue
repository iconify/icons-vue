<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drrty8bwe.css';
import '../../css/d/dg2iadbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drrty8bwe"/><path clip-rule="evenodd" class="dg2iadbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:unlocked-2" /></template>
