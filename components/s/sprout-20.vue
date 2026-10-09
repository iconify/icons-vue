<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db7nnwbjm.css';
import '../../css/j/jdfj84bsl.css';
import '../../css/k/ka2s7tbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="db7nnwbjm"/><path class="jdfj84bsl"/><path class="ka2s7tbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sprout-20" /></template>
