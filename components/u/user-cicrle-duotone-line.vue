<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mxc6vr24n.css';
import '../../css/p/ptr3-9b_e.css';
import '../../css/v/vf7wv5bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="mxc6vr24n"/><circle class="ptr3-9b_e"/><path class="vf7wv5bfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-cicrle-duotone-line" /></template>
