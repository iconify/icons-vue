<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htw209bkb.css';
import '../../css/j/j95qubcnh.css';
import '../../css/x/xpavwbcrh.css';
import '../../css/v/vu9ry25jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htw209bkb wm-a"/><path class="j95qubcnh wm-k"/><path class="wm-k xpavwbcrh"/><path class="vu9ry25jl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:unlock" /></template>
