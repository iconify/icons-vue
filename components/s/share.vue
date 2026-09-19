<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jrxssqnyz.css';
import '../../css/r/rzyzgqcqn.css';
import '../../css/t/ticjgqbdl.css';
import '../../css/f/fex6dubso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="jrxssqnyz"/><circle class="rzyzgqcqn"/><circle class="ticjgqbdl"/><path class="fex6dubso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:share" /></template>
