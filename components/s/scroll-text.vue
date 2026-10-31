<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w5v-28hwz.css';
import '../../css/k/k_fnqcbfy.css';
import '../../css/s/s_d5lc1ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w5v-28hwz wm-k"/><path class="k_fnqcbfy wm-shine"/><path class="s_d5lc1ez wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:scroll-text" /></template>
