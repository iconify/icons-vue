<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eu6knub9g.css';
import '../../css/n/n4b9algmz.css';
import '../../css/k/k_oq4vuij.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/a/agp8ui-vm.css';
import '../../css/s/shjp9pbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eu6knub9g"/><path class="n4b9algmz"/><path class="k_oq4vuij"/><g class="mc2zb0bvp"><path class="agp8ui-vm"/><path class="shjp9pbqe"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-4-bold-duotone" /></template>
