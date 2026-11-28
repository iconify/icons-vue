<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp75s3bpj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sggxujywz.css';
import '../../css/t/tod053bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp75s3bpj secondary"/><g class="dt0cm9dhy primary"><path class="sggxujywz"/><path class="tod053bcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pennant-duo" /></template>
