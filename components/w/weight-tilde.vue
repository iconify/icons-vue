<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rl_p2s3kc.css';
import '../../css/x/xi4n6f8tg.css';
import '../../css/k/k45hr2bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rl_p2s3kc"/><path class="xi4n6f8tg"/><circle class="k45hr2bcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:weight-tilde" /></template>
