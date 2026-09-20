<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bo7bp7bqb.css';
import '../../css/g/gzlm1jb-p.css';
import '../../css/q/qe99iznek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bo7bp7bqb"/><path class="gzlm1jb-p"/><path class="qe99iznek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sthetoscope" /></template>
