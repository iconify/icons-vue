<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0j56bbrs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/ll59ytbdg.css';
import '../../css/h/h9q9mhboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0j56bbrs secondary"/><g class="dt0cm9dhy primary"><path class="ll59ytbdg"/><circle class="h9q9mhboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:settings-duo" /></template>
