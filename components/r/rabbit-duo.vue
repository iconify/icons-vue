<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxonbs3hx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r9gp6qf-j.css';
import '../../css/s/suapyh5qh.css';
import '../../css/a/acylhpecb.css';
import '../../css/a/akzg8c5xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxonbs3hx secondary"/><g class="dt0cm9dhy primary"><path class="r9gp6qf-j"/><path class="suapyh5qh"/><path class="acylhpecb"/><path class="akzg8c5xz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rabbit-duo" /></template>
