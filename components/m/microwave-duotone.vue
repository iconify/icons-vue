<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lp9fgvh8r.css';
import '../../css/s/s3fhr-boy.css';
import '../../css/n/numid2z_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lp9fgvh8r"/><path class="s3fhr-boy"/><path class="numid2z_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:microwave-duotone" /></template>
