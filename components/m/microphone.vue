<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_mc4ya_v.css';
import '../../css/z/z56-4sbhg.css';
import '../../css/j/juse7d_jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a x_mc4ya_v"/><path class="wm-k z56-4sbhg"/><path class="juse7d_jr wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:microphone" /></template>
