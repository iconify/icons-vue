<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x25z2o0be.css';
import '../../css/o/o11niq9fb.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/l/lzfr0mu0h.css';
import '../../css/t/t_c730b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="x25z2o0be"/><path class="o11niq9fb"/><g class="mc2zb0bvp"><path class="lzfr0mu0h"/><path class="t_c730b3w"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-off-bold-duotone" /></template>
