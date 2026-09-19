<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m1ajpyfbs.css';
import '../../css/f/f9l7gbbmg.css';
import '../../css/u/uztmj3dza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m1ajpyfbs"/><path class="f9l7gbbmg"/><path class="uztmj3dza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:n-th-root-square" /></template>
