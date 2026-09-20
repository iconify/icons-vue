<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/md1uaibwm.css';
import '../../css/f/fblsodb-h.css';
import '../../css/k/kxcghxbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="md1uaibwm"/><path class="fblsodb-h"/><path class="kxcghxbfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-vertical-bold" /></template>
