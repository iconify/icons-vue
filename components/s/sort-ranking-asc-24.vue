<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl4fp4vpe.css';
import '../../css/p/p_sp1no_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl4fp4vpe"/><path clip-rule="evenodd" class="p_sp1no_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-ranking-asc-24" /></template>
