<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxe5v-hkz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q4yhjob_q.css';
import '../../css/s/su_j4xs_x.css';
import '../../css/j/js8xzdbuz.css';
import '../../css/e/e_rlgbb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sxe5v-hkz"/><g class="dt0cm9dhy primary"><path class="q4yhjob_q"/><path class="su_j4xs_x"/><path class="js8xzdbuz"/><path class="e_rlgbb6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:qr-code-duo" /></template>
