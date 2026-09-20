<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bode0t1-k.css';
import '../../css/a/az5r9nb_t.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/x/xqp3lqbhw.css';
import '../../css/m/mewnltmzk.css';
import '../../css/s/si33jlbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bode0t1-k"/><path class="az5r9nb_t"/><g class="jn8qy4bru"><path class="xqp3lqbhw"/><path class="mewnltmzk"/><path class="si33jlbhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mouse" /></template>
