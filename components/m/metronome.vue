<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pw778mbpo.css';
import '../../css/n/n-fw9sbnf.css';
import '../../css/g/gqayovb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pw778mbpo"/><circle class="n-fw9sbnf"/><path class="gqayovb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:metronome" /></template>
