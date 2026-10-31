<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7ephwb-o.css';
import '../../css/t/t_ciu4b3h.css';
import '../../css/g/gbjdtbbzz.css';
import '../../css/b/ba1owlbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="x7ephwb-o"/><path class="t_ciu4b3h"/><path class="gbjdtbbzz"/><path class="ba1owlbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:niger" /></template>
