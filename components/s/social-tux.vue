<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/ki4vmlb-h.css';
import '../../css/f/fqwam5hgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="cuyn6tgcc"><path class="ki4vmlb-h"/><path class="fqwam5hgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-tux" /></template>
