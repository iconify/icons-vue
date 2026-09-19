<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/z-lw6rbxb.css';
import '../../css/u/u9ousftuv.css';
import '../../css/p/p-psffbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="z-lw6rbxb"/><path class="u9ousftuv"/><path class="p-psffbzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tools" /></template>
